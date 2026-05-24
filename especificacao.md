# 3. DOCUMENTO DE ESPECIFICAÇÃO DE REQUISITOS DE SOFTWARE

Constarão a seguir os detalhamentos dos requisitos do sistema 

## 3.1 Objetivos deste documento
Descrever e especificar as necessidades dos Usuários que utilizarão o nosso sistema de auxílio a gerenciamento de tarefas com ênfase em design voltado a neurodivergentes. 

## 3.2 Escopo do produto

### 3.2.1 Nome do produto e seus componentes principais
O produto será um Sistema de Gerenciamento de Tarefas e Metas com o nome “(Ainda não decidimos)”, ele será composto por três componentes (módulos), com elementos necessários à criação de metas / checklists diários, projetos a longo prazo e atividades semanais para realizar estes projetos. 

### 3.2.2 Missão do produto
Disponibilizar uma plataforma inclusiva para todos os indivíduos, porém com foco em pessoas que possuem TDAH, para auxiliar na parte de organização e construção de rotina e metas a longo prazo. 

### 3.2.3 Limites do produto
O Sistema de Gerenciamento de Tarefas não terá sugestões de tratamento e medicação, será apenas uma ferramenta de auxílio para os usuários. Ele deve procurar um profissional qualificado para avaliar qual será a melhor estratégia de tratamento já que ele é muito individualizado nos casos de TDAH. 

### 3.2.4 Benefícios do produto

| # | Benefício | Valor para o Cliente |
|--------------------|------------------------------------|----------------------------------------|
|1	| Facilidade na criação e remoção de tarefas diárias  |	Essencial |
|2 | Facilidade na recuperação de informações | Essencial | 
|3 | Segurança no cadastro de matrículas | Essencial | 
|4	| Melhoria na comunicação com os alunos	| Essencial | 
|5	| Engajamento por gamificação 	| Essencial |
|6	| Desenvolvimento de rotina / sistema de engajamento e incentivo para login diário 	| Essencial |
|7	| Área de artigos / conscientização sobre TDAH 	| Médio |
|8	| Fórum de usuários para registros diários e comunicação / criação de senso de comunidade 	| Alto |

## 3.3 Descrição geral do produto

### 3.3.1 Requisitos Funcionais

| Código | Requisito Funcional | Descrição |
|--------|--------------------|----------|
| RF1 | Gerenciar Usuários | Processamento de Criação, Exclusão e Edição de Usuários. |
| RF2 | Gerenciar tarefas | Processamento de Criação, Exclusão, Consulta e Conclusão de tarefas. |
| RF3 | Acumular pontos e experiência | Processamento para adicionar os pontos e experiência ao personagem após finalizar tarefas. |
| RF4 | Subir de Nível | Processamento para aumentar o nível do personagem após alcançar a quantidade de experiência necessária. |
| RF5 | Gerenciar hábitos | Processamento de Inclusão, Alteração, Consulta de tarefas recorrentes. |
| RF6 | Administração de pontos acumulados | Sistema para utilização dos pontos em recompensas. |
| RF7 | Personalizar o avatar | Processamento de alteração do visual do avatar: vestuário, acessórios, background, pets. |
| RF8 | Gerenciamento de Agenda | Processamento de inclusão e alteração de prazos nas tarefas com prazo limite, personalização de tarefas "extras" fora da rotina. |
| RF9 | Consultar tarefas | Processamento de consulta de tarefas por palavra-chave ou nome. |

### 3.3.2 Requisitos Não Funcionais

| Código | Descrição |
|--------|----------|
| RNF1 | Produto terá restrição de acesso às contas individuais por meio de login e senha. |
| RNF2 | O sistema terá interface intuitiva, facilitando a utilização e navegação. |
| RNF3 | O sistema contará com tempo de resposta de no máximo 500ms em condições normais de operação. |
| RNF4 | O ambiente operacional será Windows, com compatibilidade para os navegadores Google Chrome, Brave, Firefox, Microsoft Edge e Safari. |
| RNF5 | O sistema deverá ter um uptime de >99,9% em condições normais. |
| RNF6 | O sistema terá conformidade com a LGPD para armazenamento de dados. |
| RNF7 | A arquitetura do código permitirá escalabilidade horizontal para suprir aumento de tráfego futuro. |
| RNF8 | O sistema deverá suportar "X" usuários simultâneos sem degradação no tempo de resposta. |

### 3.3.3 Usuários 

| # | Ator | Definição |
|---|------|----------|
| 1 | Administrador | Usuário responsável por testes de novas features, aprovação de parceiros e moderação dos fóruns / sistemas de comunicação entre usuários. |
| 2 | Usuário Comum | Usuário responsável por cadastrar tarefas, definir prioridades e concluir atividades. Pode também personalizar seu avatar, visualizar recompensas, interagir com o sistema de pontuação, melhorando sua organização e produtividade. |

## 3.4 Modelagem do Sistema

### 3.4.1 Diagrama de Casos de Uso
Como observado no diagrama de casos de uso da Figura 1, a secretária poderá gerenciar as matrículas e professores no sistema, enquanto o coordenador, além dessas funções, poderá gerenciar os cursos de aperfeiçoamento.

#### Figura 1: Diagrama de Casos de Uso do Sistema.

<img width="702" height="401" alt="image" src="https://github.com/user-attachments/assets/ba8fbad2-3a3b-4061-8708-81209c0c8b81" />
<img width="684" height="608" alt="image" src="https://github.com/user-attachments/assets/143c4124-cb83-4e81-8bac-8c2645b679de" />

 
### 3.4.2 Descrições de Casos de Uso

Descrições de casos de uso

## Casos de Uso

---

### Cadastro de Usuário (CSU01)

**Sumário:** O Usuário realiza o cadastro na plataforma, preenchendo as credenciais para acesso.  

**Ator Primário:** Usuário Comum  
**Ator Secundário:** Nenhum  

**Pré-condições:** O Usuário deve possuir acesso ao sistema e não estar previamente cadastrado.  

**Fluxo Principal:**
1. O Usuário acessa a tela inicial e solicita o cadastro.  
2. O Sistema apresenta um formulário de cadastro.  
3. O Usuário preenche nome, e-mail e senha.  
4. O Sistema valida os dados informados.  
5. O Sistema cria a conta e redireciona o Usuário para a tela inicial.  

**Fluxo Alternativo (E-mail já cadastrado):**
- O Sistema identifica que o e-mail já está em uso.  
- O Sistema exibe mensagem de erro.  
- O Usuário pode inserir outro e-mail ou redefinir senha.  

**Fluxo Alternativo (Dados inválidos):**
- O Sistema identifica campos inválidos.  
- O Sistema destaca os campos incorretos.  

**Pós-condições:** Conta criada com sucesso.  

---

### Gerenciar Tarefas (CSU02)

**Sumário:** O Usuário realiza a gestão das tarefas.  

**Ator Primário:** Usuário Comum  
**Pré-condições:** Usuário autenticado  

**Fluxo Principal:**
1. Usuário acessa o menu de tarefas.  
2. Sistema exibe opções: incluir, alterar, excluir, consultar.  
3. Usuário escolhe a ação desejada.  

**Fluxo Alternativo (Inclusão):**
- Usuário cria nova tarefa.  
- Preenche título, descrição e prioridade.  
- Sistema valida e salva.  

**Fluxo Alternativo (Alteração):**
- Usuário seleciona tarefa.  
- Altera dados.  
- Sistema atualiza.  

**Fluxo Alternativo (Exclusão):**
- Usuário seleciona tarefa.  
- Sistema pede confirmação.  

**Fluxo Alternativo (Consulta):**
- Usuário busca por nome ou palavra-chave.  

**Pós-condições:** Tarefa gerenciada com sucesso.  

---

### Concluir Tarefas (CSU03)

**Sumário:** O Usuário conclui tarefas.  

**Fluxo Principal:**
1. Usuário acessa lista de tarefas.  
2. Marca tarefa como concluída.  
3. Sistema atualiza status.  
4. Sistema adiciona pontos.  

**Pós-condições:** Tarefa concluída e pontos adicionados.  

---

### Sistema de Pontuação (CSU04)

**Sumário:** Sistema atribui pontos ao Usuário.  

**Fluxo Principal:**
1. Sistema identifica tarefa concluída.  
2. Verifica prioridade.  
3. Calcula pontos.  
4. Atualiza perfil do usuário.  

---

### Sistema de Níveis (CSU05)

**Sumário:** Sistema gerencia evolução de nível.  

**Fluxo Principal:**
1. Sistema verifica pontos.  
2. Calcula progresso.  
3. Atualiza nível.  
4. Libera recompensas.  

---

### Sistema de Recompensas (CSU06)

**Sumário:** Usuário troca pontos por recompensas.  

**Fluxo Principal:**
1. Usuário acessa loja.  
2. Escolhe recompensa.  
3. Sistema verifica pontos.  
4. Realiza troca.  

**Fluxo Alternativo:**
- Pontos insuficientes → sistema informa erro.  

---

### Personalizar Avatar (CSU07)

**Sumário:** Usuário personaliza avatar.  

**Fluxo Principal:**
1. Usuário acessa personalização.  
2. Sistema mostra itens disponíveis.  
3. Usuário seleciona item.  
4. Sistema aplica alteração.  

---

### Criar Subtarefa (CSU08)

**Sumário:** Usuário divide tarefas em subtarefas.  

**Fluxo Principal:**
1. Usuário seleciona tarefa.  
2. Escolhe adicionar subtarefa.  
3. Preenche descrição.  
4. Sistema salva subtarefa.  

---

### Definir Prioridade (CSU09)

**Sumário:** Usuário define prioridade da tarefa.  

**Fluxo Principal:**
1. Usuário seleciona tarefa.  
2. Escolhe prioridade (baixa, média, alta).  
3. Sistema salva.  

---

### Definir Prazo (CSU10)

**Sumário:** Usuário define prazo da tarefa.  

**Fluxo Principal:**
1. Usuário seleciona tarefa.  
2. Define nova data.  
3. Sistema atualiza.  

**Fluxo Alternativo:**
- Data inválida → sistema exibe erro.  

---

### Buscar Tarefas (CSU11)

**Sumário:** Usuário busca tarefas.  

**Fluxo Principal:**
1. Usuário digita palavra-chave.  
2. Sistema realiza busca.  
3. Exibe resultados.  

**Fluxo Alternativo:**
- Nenhuma tarefa encontrada.  

---

### 3.4.3 Diagrama de Classes 

A Figura 2 mostra o diagrama de classes do sistema. A Matrícula deve conter a identificação do funcionário responsável pelo registro, bem com os dados do aluno e turmas. Para uma disciplina podemos ter diversas turmas, mas apenas um professor responsável por ela.

#### Figura 2: Diagrama de Classes do Sistema.
 
<img width="989" height="545" alt="image" src="https://github.com/user-attachments/assets/cd5c293f-9645-44c8-be6d-b0002e89a1e6" />



### 3.4.4 Descrições das Classes 


| # | Nome | Descrição |
|---|------|-----------|
| 1 | Usuario | Classe base que representa qualquer usuário do sistema, contendo as informações de autenticação e identificação. |
| 2 | UsuarioComum | Usuário final da plataforma, responsável por gerenciar tarefas, acumular pontos e interagir com o sistema de gamificação. |
| 3 | Administrador | Usuário com privilégios elevados, responsável por moderar o fórum, aprovar parceiros e testar novas funcionalidades. |
| 4 | Tarefa | Representa uma atividade criada pelo usuário, com título, descrição, prioridade, prazo e status de conclusão. |
| 5 | Subtarefa | Divisão de uma tarefa complexa em etapas menores, facilitando a execução gradual da atividade. |
| 6 | Habito | Tarefa recorrente configurada pelo usuário, com frequência definida e controle de sequência (streak). |
| 7 | Agenda | Gerencia os prazos e eventos associados às tarefas, permitindo organização temporal das atividades. |
| 8 | Pontuacao | Registra os pontos e experiência (XP) ganhos pelo usuário ao concluir tarefas, alimentando o sistema de níveis. |
| 9 | Nivel | Representa a progressão do usuário na plataforma, definindo os requisitos de XP e as recompensas desbloqueadas. |
| 10 | Recompensa | Item disponível na loja da plataforma, resgatável com os pontos acumulados pelo usuário. |
| 11 | Avatar | Representa a identidade visual do usuário, personalizável com vestuário, acessórios, background e pets. |
| 12 | PostForum | Publicação feita pelo usuário no fórum da comunidade, promovendo troca de experiências entre os membros. |

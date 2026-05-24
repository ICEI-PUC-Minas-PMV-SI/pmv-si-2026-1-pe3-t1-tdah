# 4. PROJETO DO DESIGN DE INTERAÇÃO

## 4.1 Personas
Nesta seção você deve detalhar as personas do seu projeto. Deve-se documentar uma persona por integrante do projeto. Para mais informações sobre personas consulte: https://www.rdstation.com/blog/marketing/persona-o-que-e/. Sugere-se a utilização de um template do Canva: https://www.canva.com/pt_br/modelos/s/persona/

Persona 1: Lucas Silva
![Persona 1](./screenshots/persona-1.jpg)

Persona 2: Marina Albuquerque
![Persona 2](./screenshots/persona-2.jpg)

Persona 3: Roberto Mendes
![Persona 3](./screenshots/persona-3.jpg)

Persona 4: Sara Marques
![Persona 3](./screenshots/Persona-4.jpg)

## 4.2 Mapa de Empatia
Mapa da Empatia é um material utilizado para conhecer melhor o seu cliente. A partir do mapa da empatia é possível detalhar a personalidade do cliente e compreendê-la melhor. O objetivo é obter um nível mais profundo de compreensão de uma persona. A seguir um exemplo de template que pode ser usado para o mapa de empatia. Para cada persona deverá ser apresentado o seu respectivo mapa de empatia. Sugere-se a utilização do template apresentado em https://www.rdstation.com/blog/marketing/mapa-da-empatia/.

Mapa de Empatia: Lucas Silva
![Mapa 1](./screenshots/mapa-empatia-1.jpg)

Mapa de Empatia: Marina Albuquerque
![Mapa 2](./screenshots/mapa-empatia-2.jpg)

Mapa de Empatia: Roberto Mendes
![Mapa 3](./screenshots/mapa-empatia-3.jpg)

Mapa de Empatia: Sara Marques
![Mapa 3](./screenshots/Mapa-empatia-4.jpg)

## 4.3 Protótipos das Interfaces
Apresente nesta seção os protótipos de alta fidelidade do sistema proposto. A fidelidade do protótipo refere-se ao nível de detalhes e funcionalidades incorporadas a ele. Assim, um protótipo de alta fidelidade é uma representação interativa do produto, baseada no computador ou em dispositivos móveis. Esse protótipo já apresenta maior semelhança com o design final em termos de detalhes e funcionalidades. No desenvolvimento dos protótipos, devem ser considerados os princípios gestálticos, as recomendações ergonômicas e as regras de design (como as 8 regras de ouro). É importante descrever no texto do relatório como os princípios gestálticos e as regras de ouro foram seguidas no projeto das interfaces. Nesta etapa deve-se dar uma ênfase na implementação do software de modo que possam ser realizados os testes com usuários na etapa seguinte.

4.3.1 Tela de Login: Tela inicial onde o usuário realiza a autenticação na plataforma para acessar seu painel gamificado, possuindo também atalho direto para a criação de uma nova conta.
![Login](./screenshots/01-tela-login.jpg)

* **Princípios Gestálticos:**
    * **Proximidade:** Campos de e-mail e senha estão agrupados centralmente, facilitando a percepção de que formam o bloco de login.
    * **Similaridade:** Os campos de entrada possuem o mesmo estilo visual, indicando funções idênticas de inserção de texto.
    * **Continuidade:** O fluxo visual é vertical, conduzindo o olhar naturalmente do topo do formulário até o botão de confirmação.
    * **Fechamento:** O container do formulário delimita a área de preenchimento, separando o conteúdo funcional do fundo da página.
    * **Figura-Fundo:** O uso de contraste destaca a caixa de login (figura) sobre o plano de fundo (fundo), eliminando distrações visuais na web.

* **Regras de Ouro de Shneiderman:**
    * **Consistência:** A interface utiliza o padrão de cores e fontes definido no guia de estilo da plataforma web.
    * **Feedback Informativo:** O cursor do mouse muda para "pointer" ao passar sobre botões, sinalizando elementos clicáveis.
    * **Redução da Sobrecarga de Memória:** O layout é simplificado, solicitando apenas dados mínimos para evitar que o usuário precise memorizar instruções complexas.
    * **Reversão de Ações:** Botão de "Voltar" ou links de alternância permitem que o usuário mude de ideia antes de submeter os dados.

* **Recomendações Ergonômicas:**
    * **Carga de Trabalho:** O formulário curto reduz o tempo de digitação e a fadiga visual.
    * **Condução:** O design foca a atenção no centro da tela, onde ocorre a ação principal do navegador.
    * **Controle do Usuário:** Links de fácil acesso permitem que o usuário navegue para outras partes do site caso tenha entrado na página errada.
    * **Consistência:** Ícones universais de login facilitam a compreensão rápida sem necessidade de leitura densa.

4.3.2 Tela de Cadastro: Tela onde o novo usuário preenche seus dados pessoais essenciais para registrar uma conta e iniciar sua jornada de produtividade.
![Cadastro](./screenshots/02-tela-cadastro.jpg)

* **Princípios Gestálticos:**
    * **Proximidade:** Etiquetas de texto e campos de entrada estão próximos, garantindo que o usuário saiba exatamente o que preencher.
    * **Similaridade:** Todos os campos de registro seguem o mesmo padrão de design, reforçando a consistência do sistema.
    * **Continuidade:** A disposição dos campos sugere um passo a passo lógico para a criação da conta.
    * **Fechamento:** Bordas nítidas nos inputs ajudam a definir o espaço de clique para o ponteiro do mouse.
    * **Figura-Fundo:** O formulário de registro é o elemento de maior peso visual na página, destacando-se contra o background estilizado.

* **Regras de Ouro de Shneiderman:**
    * **Consistência:** Mantém os mesmos componentes visuais da tela de login para reforçar o aprendizado do usuário no site.
    * **Feedback Informativo:** Validações de formulário indicam erros de preenchimento antes mesmo do envio final.
    * **Redução da Sobrecarga de Memória:** Placeholders dentro dos campos auxiliam o preenchimento sem exigir que o usuário decore o que cada campo pede.
    * **Reversão de Ações:** O usuário pode limpar os campos ou retornar à página anterior através da navegação nativa do navegador.

* **Recomendações Ergonômicas:**
    * **Carga de Trabalho:** Estrutura enxuta para não desencorajar o novo usuário com formulários excessivamente longos.
    * **Condução:** O layout guia o preenchimento de cima para baixo, finalizando no botão de chamada para ação (CTA).
    * **Controle do Usuário:** Oferece opções de visualização de senha para conferência antes da confirmação.
    * **Consistência:** Estética visual alinhada com as demais páginas do ecossistema web do projeto.

4.3.3 Interface principal do sistema organizada em colunas para a gestão de hábitos e tarefas. O diferencial é o sistema de RPG, onde o usuário ganha pontos de experiência (XP) ou recupera vida (HP) ao concluir suas obrigações diárias, transformando a produtividade em um jogo.
![Dashboard](./screenshots/03-tela-dashboard.jpg)

* **Princípios Gestálticos:**
    * **Proximidade:** Tarefas são agrupadas em colunas (Hábitos, Diárias, Metas), organizando o fluxo de trabalho por categorias.
    * **Similaridade:** Cards de tarefas possuem a mesma estrutura visual, permitindo que o usuário identifique o padrão de interação.
    * **Continuidade:** O alinhamento horizontal das colunas incentiva a navegação lateral e o planejamento sequencial.
    * **Fechamento:** Cada card é uma unidade independente, facilitando a distinção entre diferentes obrigações no painel.
    * **Figura-Fundo:** As barras de HP e XP no cabeçalho destacam-se como elementos de status persistentes sobre a área de trabalho.

* **Regras de Ouro de Shneiderman:**
    * **Consistência:** A barra de navegação lateral (menu) permanece fixa, facilitando o acesso a outras áreas da aplicação web.
    * **Feedback Informativo:** Mudanças visuais imediatas nas barras de progresso ao concluir uma tarefa (gamificação em tempo real).
    * **Redução da Sobrecarga de Memória:** O formato Kanban organiza a carga mental, exibindo as tarefas em blocos digeríveis.
    * **Reversão de Ações:** Permite desmarcar tarefas, corrigindo o ganho de experiência ou perda de vida de forma instantânea.

* **Recomendações Ergonômicas:**
    * **Carga de Trabalho:** A divisão da rotina em colunas reduz a sensação de sobrecarga comum em usuários com TDAH.
    * **Condução:** Elementos visuais coloridos (verde, vermelho, amarelo) indicam prioridades e status de saúde do avatar.
    * **Controle do Usuário:** Autonomia para criar, deletar e reordenar tarefas conforme a necessidade individual.
    * **Consistência:** Uso de ícones padrão de jogos que comunicam significado sem depender exclusivamente de texto.

4.3.4 Tela de Inventário: Tela onde são listados os itens e recompensas virtuais adquiridos pelo usuário na loja da plataforma, com opção de filtros laterais por categorias específicas (pets, equipamentos, etc.).
![Inventário](./screenshots/04-tela-inventario.jpg)

* **Princípios Gestálticos:**
    * **Proximidade:** Os itens colecionáveis são dispostos em grade, permitindo a comparação visual rápida.
    * **Similaridade:** Todos os slots de inventário possuem o mesmo formato, padronizando a exibição das conquistas.
    * **Continuidade:** A grade direciona a varredura visual organizada, típica de sistemas de gerenciamento de arquivos.
    * **Fechamento:** Bordas de cada slot "fecham" a área do item, facilitando a precisão do clique com o mouse.
    * **Figura-Fundo:** O fundo escuro dos slots destaca os ícones dos equipamentos, dando foco ao valor estético das recompensas.

* **Regras de Ouro de Shneiderman:**
    * **Consistência:** A identidade visual dos itens é mantida desde a conquista até a visualização no perfil.
    * **Feedback Informativo:** Realce visual (borda ou brilho) indica qual item está atualmente equipado no personagem.
    * **Redução da Sobrecarga de Memória:** O sistema de filtros (abas laterais) elimina a necessidade de procurar itens em listas longas.
    * **Reversão de Ações:** Permite equipar e trocar acessórios livremente, sem limites de tentativas.

* **Recomendações Ergonômicas:**
    * **Carga de Trabalho:** Organização em categorias que permite ao usuário focar apenas em uma parte do equipamento por vez.
    * **Condução:** Navegação lateral intuitiva que conduz o usuário entre as diferentes classes de itens.
    * **Controle do Usuário:** Oferece gestão completa sobre os itens adquiridos e a estética do avatar.
    * **Consistência:** Mantém os padrões de navegação e menu vistos na Dashboard.

4.3.5 Tela Perfil: Tela funcionando como painel de controle flutuante, onde o usuário edita seus dados de cadastro, ajusta o nome de exibição do seu avatar e acompanha suas estatísticas básicas.
![Perfil](./screenshots/05-modal-perfil.jpg)

* **Princípios Gestálticos:**
    * **Proximidade:** Informações de usuário e estatísticas de progresso estão agrupadas em seções temáticas claras.
    * **Similaridade:** Elementos de edição (botões e campos) seguem o padrão visual de toda a aplicação web.
    * **Continuidade:** Layout vertical que guia a leitura da imagem do avatar até os dados de performance na base.
    * **Fechamento:** O uso de modais ou seções delimitadas isola as configurações de perfil do restante da interface.
    * **Figura-Fundo:** O avatar centralizado atua como a figura principal, reforçando a identidade pessoal do usuário.

* **Regras de Ouro de Shneiderman:**
    * **Consistência:** Mantém o uso das mesmas cores e fontes de status que o usuário já aprendeu na Dashboard.
    * **Feedback Informativo:** Mensagens de confirmação indicam que as alterações de perfil foram salvas com sucesso no servidor.
    * **Redução da Sobrecarga de Memória:** Exibe apenas métricas fundamentais de progresso, evitando poluição visual com dados secundários.
    * **Reversão de Ações:** Botão de "Cancelar" ou "Fechar" permite sair da tela de edição sem aplicar mudanças indesejadas.

* **Recomendações Ergonômicas:**
    * **Carga de Trabalho:** Interface focada apenas na identidade, livre de elementos de gestão de tarefas.
    * **Condução:** Organização hierárquica que prioriza a imagem do usuário seguida de suas conquistas.
    * **Controle do Usuário:** Liberdade para personalizar a representação digital do usuário no sistema.
    * **Consistência:** Uso de medalhas e ícones de experiência que conversam com a linguagem de RPG do site.


4.3.6 Tela de Loja: Tela onde o usuário pode utilizar suas moedas de ouro, adquiridas ao completar tarefas, para comprar novos itens, equipamentos e pets para personalizar o seu avatar.
![Loja](./screenshots/06-tela-loja.jpg)

* **Princípios Gestálticos:**
    * **Proximidade:** O preço em ouro está posicionado imediatamente abaixo do ícone de cada item, criando uma associação direta entre o produto e o seu valor.
    * **Similaridade:** Os itens à venda utilizam o mesmo padrão de card, facilitando o reconhecimento instantâneo de que todos são produtos interativos e compráveis.
    * **Continuidade:** A disposição em grade induz o usuário a explorar o catálogo navegando de forma linear, visualizando as opções linha por linha.
    * **Fechamento:** Cada slot de item possui um contorno que agrupa a imagem, o preço e o botão de compra em uma única unidade visual de decisão.
    * **Figura-Fundo:** Itens indisponíveis por falta de saldo ou já adquiridos recebem uma camada de opacidade, mantendo o foco (figura) apenas nos itens que o usuário pode comprar.

* **Regras de Ouro de Shneiderman:**
    * **Consistência:** O layout de grade e os filtros laterais replicam a exata estrutura e identidade visual da tela de Inventário, aproveitando o aprendizado prévio do usuário.
    * **Feedback Informativo:** Os botões mudam de estado dinamicamente (ex: assumindo os textos "Adquirido" ou "Ouro Insuficiente") dependendo do saldo e do inventário do usuário.
    * **Redução da Sobrecarga de Memória:** O saldo atual de ouro fica fixo e bem visível no cabeçalho superior, dispensando a necessidade de o usuário memorizar ou buscar quanto possui.
    * **Reversão de Ações:** Ao clicar em comprar, um modal de confirmação é acionado antes da transação, protegendo o usuário de compras acidentais e impulsivas.

* **Recomendações Ergonômicas:**
    * **Carga de Trabalho:** O menu de filtros laterais permite isolar categorias específicas de itens (como apenas Pets ou Peitorais), evitando a fadiga de analisar uma lista muito longa.
    * **Condução:** O botão principal de compra em destaque e os preços coloridos guiam o olhar direto para as informações essenciais de conversão.
    * **Controle do Usuário:** O usuário tem autonomia total para navegar livremente entre as abas e decidir estrategicamente como investir as recompensas de sua produtividade.
    * **Consistência:** A navegação superior e os padrões de botões de fechamento de modais mantêm a mesma usabilidade encontrada no restante da plataforma.

## 4.4 Testes com Protótipos

Nesta etapa foram realizados testes de usabilidade utilizando o protótipo de alta fidelidade do sistema **TaskUp**. O objetivo foi avaliar a experiência do usuário, analisando a facilidade de navegação, clareza das informações e eficiência das funcionalidades presentes no sistema.

Os testes foram aplicados com usuários alinhados ao perfil das personas definidas anteriormente no projeto.

---

### Participante do Teste

- **Nome:** Lucas Geraldi  
- **Idade:** 46 anos  
**Data:** 08/05/26  
**Participante Nº:** 1

---

### Tarefas Realizadas

Durante o teste, o participante executou as seguintes tarefas:

1. Realizar login no sistema;
2. Adicionar uma nova tarefa;
3. Marcar hábitos como concluídos;
4. Visualizar recompensas disponíveis;
5. Consultar o progresso do perfil.

---

### Resultados Observados

| Tarefa | Tempo Médio | Observações |
|---|---|---|
| Login no sistema | 1 minuto | Processo rápido e intuitivo |
| Adicionar tarefa | 2 minutos | Pequena dúvida sobre categorias |
| Concluir hábitos | 1 minuto | Fácil interação com os botões |
| Visualizar recompensas | 2 minutos | Dificuldade em entender alguns ícones |
| Consultar progresso | 1 minuto | Informações consideradas claras |

---

### Feedback do Usuário

#### Pontos Positivos
- Interface moderna e organizada;
- Navegação simples e intuitiva;
- Sistema de gamificação motivador;
- Boa organização visual das tarefas;
- Fácil acompanhamento do progresso.

#### Pontos Negativos
- Alguns ícones não ficaram totalmente claros;
- Certas funções poderiam ter maior destaque visual;
- Algumas informações possuem pouco contraste.

---

### Análise Geral

Os testes demonstraram que o sistema **Daily&Quest** possui uma interface intuitiva e de fácil utilização. O participante conseguiu realizar todas as tarefas propostas sem grandes dificuldades, demonstrando boa usabilidade e compreensão das funcionalidades.

A mecânica de gamificação foi considerada um dos principais pontos positivos do projeto, ajudando na motivação e no acompanhamento das atividades diárias.

Apesar dos resultados positivos, foram identificadas oportunidades de melhoria relacionadas à acessibilidade visual e à clareza de alguns elementos da interface.

---

### Melhorias Previstas

Com base nos testes realizados, foram definidas as seguintes melhorias para a versão final do projeto:

- Adicionar descrições em ícones;
- Melhorar contraste visual de alguns elementos;
- Destacar funções principais da interface;
- Simplificar categorias de tarefas;
- Inserir mensagens de ajuda para novos usuários.


# Relatório de Teste com Usuário

Projeto: TaskUp

Equipe: SI-pe3-project-TDAH

---

**Nome do avaliador:** Arthur Rocha Furtado  
**Data:** 09/05/26  
**Participante Nº:** 2

---

## Proposta

A proposta deste teste é verificar o entendimento e usabilidade do projeto desenvolvido a partir das interações do usuário representativo do público-alvo. O teste também será utilizado para testar o público geral e avaliar inconsistências e satisfação em relação à interface e usabilidade.

---

## Questões Introdutórias e Tarefas

### Familiaridade com o sistema

**Pergunta:**  
“Você já ouviu falar ou está familiarizado com esse tipo de sistema?”

- [ ] SIM
- [x] NÃO

*Caso sim, desenvolva a resposta.*

---

### Impressão inicial da tela

**Pergunta:**  
“Olhando para essa tela, que tipo de informação você pode obter?”

> Pelo que se pode ver é um aplicativo para “marcar” tarefas, você adiciona as tarefas e vai marcando com um mais ou menos dependendo se foi feito. Também tem o personagem que vai subindo de nível provavelmente quando completa as coisas, não entendi muito como que consegue as moedas.

---

### Objetivo percebido do sistema

**Pergunta:**  
“Para que você acha que o sistema foi desenvolvido?”

> Para ser uma forma de “lista” de compromissos e tarefas diárias mais descontraído. Para ficar um pouco diferente e parece que dá mais vontade de abrir e fazer as coisas mesmo sem ser tudo cinza, preto e branco.

---

### Clareza da interface

**Pergunta:**  
“Você acha que está fácil de entender o que dá pra fazer logo de cara? Fica alguma coisa confusa na tela?”

> Acho que dá sim, sem clicar em nada só fica meio confuso essa questão das moedas e da loja sobre como funciona, mas dá pra ter uma ideia.

---

## Cenário

Descreva neste campo um cenário (definido o contexto) em que o sistema pode estar inserido no momento de uso para apresentar para o usuário.

---

# Tarefas para o Usuário

| Tarefa | Caminho(s) | Sucesso na execução | Observações |
|---|---|---|---|
| Criar uma tarefa | Clicar em adicionar tarefa, escolher se será hábito, diário ou desafio | 2 | Layout intuitivo, o botão está num lugar bem chamativo logo acima das sessões de tarefas. |
| Completar uma tarefa | Clicar no “+” ao lado da tarefa para completá-la | 2 | Usuário completou a tarefa em poucos segundos, apenas observou que o “+” deveria ficar à direita e o “-” à esquerda. |
| Marcar que uma tarefa não foi realizada | Usuário deverá apertar o “-” ao lado da tarefa | 2 | Usuário completou em poucos segundos. |
| Filtrar algum hábito pela seleção de procura | Usuário deverá clicar na aba “Buscar ou adicionar hábito...” e procurar o hábito desejado | 2 | Usuário comentou que era redundante a parte do “adicionar hábito”, já que existe o botão acima. Também sugeriu uma única barra de busca para todas as categorias. |

---

## Legenda de Sucesso

- **0** → Não conseguiu completar  
- **1** → Completou com dificuldade ou ajuda  
- **2** → Completou sem dificuldades

# Relatório de Teste com Usuário

Projeto: TaskUp

Equipe: SI-pe3-project-TDAH

---

**Nome do avaliador:** Bruna Ribeiro Perez  
**Data:** 10/05/26  
**Participante Nº:** 3

---

## Proposta

A proposta deste teste é verificar o entendimento e usabilidade do projeto desenvolvido a partir das interações do usuário representativo do público-alvo. O teste também será utilizado para testar o público geral e avaliar inconsistências e satisfação em relação à interface e usabilidade.

---

## Questões Introdutórias e Tarefas

### Familiaridade com o sistema

**Pergunta:**  
“Você já ouviu falar ou está familiarizado com esse tipo de sistema?”

- [x] SIM
- [ ] NÃO

*Caso sim, desenvolva a resposta.*

> Já tinha ouvido falar em um parecido, chamado Habitica.

---

### Impressão inicial da tela

**Pergunta:**  
“Olhando para essa tela, que tipo de informação você pode obter?”

> É um estilo de aplicativo para marcar hábitos/tarefas, com um personagem que vai evoluindo à medida que você vai realizando as tarefas no dia a dia.

---

### Objetivo percebido do sistema

**Pergunta:**  
“Para que você acha que o sistema foi desenvolvido?”

> Provavelmente para ajudar a organizar melhor a rotina, principalmente de quem tem problema para lembrar das coisas.

---

### Clareza da interface

**Pergunta:**  
“Você acha que está fácil de entender o que dá para fazer logo de cara? Fica alguma coisa confusa na tela?”

> Parece que sim, dá para ter uma ideia boa de como funcionam as coisas só de bater o olho na tela.

---

## Cenário

Descreva neste campo um cenário (definido o contexto) em que o sistema pode estar inserido no momento de uso para apresentar para o usuário.

---

# Tarefas para o Usuário

| Tarefa | Caminho(s) | Sucesso na execução | Observações |
|---|---|---|---|
| Criar uma tarefa | Clicar em adicionar tarefa, escolher se será hábito, diário ou desafio | 2 | Usuário adicionou uma nova tarefa sem apresentar nenhum problema. |
| Completar uma tarefa | Clicar no “+” ao lado da tarefa para completá-la | 2 | Usuário apertou o “+” instintivamente, tarefa realizada sem problemas. |
| Marcar que uma tarefa não foi realizada | Usuário deverá apertar o “-” ao lado da tarefa | 2 | Novamente sem nenhum problema, usuário clicou diretamente no “-”. |
| Filtrar algum hábito pela seleção de procura | Usuário deverá clicar na aba “Buscar ou adicionar hábito...” e procurar o hábito desejado | 2 | Comentário feito sobre existir uma sessão de pesquisa separada para cada tipo de atividade/tarefa. Usuário sugeriu centralizar tudo em apenas uma aba de procura. |

---

## Legenda de Sucesso

- **0** → Não conseguiu completar  
- **1** → Completou com dificuldade ou ajuda  
- **2** → Completou sem dificuldades



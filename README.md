# Teste para vaga de desenvolvedor Front-end

## Marketplace
Grande empresa do ramo de varejo procura equipe para construir portal administrativo de gerenciamento dos produtos internos e externos para um dos maiores marketplaces do Brasil.

## Equipe
Equipe de front-end será composta de desenvolvedores de todos os níveis para atender as demandas dos diversos produtos da empresa.

## Vagas
As especificações disponíveis para as vagas são:
- Existem diversas vagas de todos os níveis: júnior, pleno e sênior.
- Situada no ABC de São Paulo.
- Boa localização e em frente a uma estação de trem.
- Contratação PJ com salários de 6k a 9k mensais.

## Especificações do teste:
Este teste engloba o fluxo de trabalho básico da equipe atual, não foge das atividades cotidianas de um desenvolvedor front-end: construção do layout, aplicação de responsividade e implementação da dinâmica das telas.
O teste é composto por diversas atividades que definem a habilidade, nível profissional e experiência do desenvolvedor com relação às linguagens e ferramentas utilizadas pela equipe atual no desenvolvimento das aplicações.
O teste abaixo terá como objetivo avaliar o conhecimento técnico, skills e os pontos fortes do desenvolvedor nos seguintes critérios:
- Domínio sobre o Angular (v5.+) e suas particularidades.
- Conhecimentos sobre JavaScript, TypeScript e ES6.
- Conhecimentos sobre CSS3, SASS e Bootstrap (v4.1).
- Qualidade e legibilidade do código.
- Habilidade de abstração;
- Entendimento do conceito de componentização utilizando componentes simples e compostos.
No teste existem 3 telas para serem implementadas, deve-se escolher pelo menos 2 delas para implementar dentro da aplicação do teste.
O layout da aplicação é um tema aleatório retirado da internet e é baseado no grid do framework Bootstrap.
Quanto mais telas e funcionalidades forem implementadas utilizando técnicas, abordagens e soluções diversificadas maior a possibilidade de subir o nível de classificação da vaga oferecida ao desenvolvedor.
O layout deve ser responsivo para se adaptar apenas para o tamanho de um tablet.

### Bônus:
#### SASS/CSS/BOOTSTRAP:
O domínio sobre a junção dessas três ferramentas é um critério muito procurado pela equipe, não só na aplicação do grid e componentes (isso é básico), mas nos seguintes critérios:
- Integração do SASS do Bootstrap com a compilação da aplicação;
- Tematização e customização dos componentes do framework a partir de suas variáveis SASS (Dica: é possível chegar muito próximo do layout apenas alterando as variáveis do SASS e usando o mínimo de CSS, apenas para pequenos ajustes);
- Construção de novos componentes com as variações de cores do framework utilizando mixins;
- Utilização das classes de utilities de forma coerente;
- Atenção à detalhes: reprodução do template o mais fielmente possível à partir do desenho disponibilizado.
Objetivo: “Tematizar” o layout do bootstrap para evitar customizações repetidas e consistência de layout para páginas com funcionalidades repetidas comuns em sistemas administrativos. Exemplo: Espaçamentos e preenchimentos, telas de listagem em tabela e formulários.

### Teste:
Desenvolva uma aplicação em Angular 5 contendo as seguintes especificações:

#### Topo e menu de navegação:
- [ ] Implementar o topo azul da página com os elementos disponíveis no layout (não precisa implementar a funcionalidade só customizar os componentes neste caso);
- [ ] Implementar um menu de navegação que possua ao menos 2 itens. Estes itens devem ser inicializados em algum local da aplicação por um array de objetos contendo o título e rota do item para popular o menu.
- [ ] Implementar um sistema de roteamento para navegar pelas páginas dos itens do menu;

#### Escolher 2 ou mais páginas para implementar:
- [ ] Dashboard:
  - [ ] Template: [Layout](/img/Teste-2.png);
  - [ ] Implementar o cabeçalho com dados que devem vir de um serviço populado por um mock dentro da aplicação;
  - [ ] Implementar o layout da primeira coluna e componente de gráfico em formato doughnut utilizando a biblioteca Chart.js (muito utilizada pela equipe atual);
  - [ ] Implementar o componente de listagem com carregamento dinâmico de dados utilizando diretivas estruturais do Angular;
  - [ ] Implementar a lógica de paginar os resultados da listagem de forma simples (não precisa fazer a paginação na prática só a lógica para não ter todos os elementos exibidos de uma vez);
  - [ ] A estilização da página deve ser feita utilizando os recursos do Bootstrap e SASS, seguindo o padrão do layout.
- [ ] Configurações:
  - [ ] Template: [Layout](/img/Teste-3.png);
  - [ ] Implementar uma tela de configurações com formulário utilizando os componentes do Bootstrap;
  - [ ] Implementar validação dos campos do formulário utilizando recursos do Angular (pode ser validação de campo obrigatório apenas);
  - [ ] Implementar uma mensagem de sucesso na submissão do formulário.

### Instruções para entrega:
- Faça um fork deste repositório e crie uma branch com o seu nome (exemplo: nome-sobrenome);
- Após finalizar o teste, faça um pull request para este repositório com o código desenvolvido;
- Documentar no README do projeto os passos necessários para rodar a aplicação.

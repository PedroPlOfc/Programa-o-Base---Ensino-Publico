## 0.1 Lógica da Programação
Primeiro, antes de você estudar tudo que você ira ver nesse arquivo, você primeiro deve ter uma noção básica de lógica de programação, recomendo pesquisar no youtube video aulas que eles explicam bem como funciona um código e o que você precisa ter de noção, a ideia aqui é apenas entender como funciona a estrutura de um código.
Após isso, você vai dar início ao Front-End, mesmo que você se interesse mais em Back-End, é importante entender como funciona o Front para usar de base na hora de aprender Back, pois ele ira ajudar no seu entendimento.
Vale lembrar que, 60% do arquivo vai ser mais uma biblioteca de comandos, 20% explicando certos conceitos, e 20% ensinando outras áreas, como controle de versões (git), e antes de mais nada, não confundam git com git hub.
## 1. Front-End
#### O que é HTML?
- HTML NÃO é uma linguagem de programação, e sim de marcação;
- Utilizamos para estruturas páginas web, criando elemento de texto, inserindo imagens, listas e formulários;
- É o esqueleto de qualquer aplicação web;
- Nós não precisamos de um software para compilar HTML;
- Podemos apenas abrir um arquivo .html no navegador e executar a linguagem;

#### O que é CSS?
- CSS é a linguagem que utilizamos para estilizar um site;
- Usamos um conjunto de HTML, a integração é super simples;
- Sem CSS, todas as páginas seriam iguais, com apenas diferença no conteúdo;
- As regras de CSS são aplicadas aos elementos do HTML;
- Podemos adicionar cores, mudar o tamanho de uma fonte, adicionar bordas aos elementos e muito mais!

#### O que é JavaScript?
O que é o JavaScript?
- JavaScript é uma Linguagem de programação de alto nível;
- Recebeu o nome por causa da linguagem java, que estava na hype;
- Entenda que: Javascript = JS = Vanilla Javascript;
- Sua principal função é deixar a página viva, adicionando comportamentos (alteraçãode HTML e CSS) através de eventos;
- JavaScript é <abbr title="Case sensitive significa que o código diferencia letras maiúsculas de minúsculas">Case Sensitive</abbr>;
#### O que é React?
- React NÃO é uma linguagem de programação, e sim uma biblioteca JavaScript para criar interfaces de usuário;
- É focado na criação de componentes reutilizáveis (como botões, cards e menus);
- Permite atualizar apenas as partes da página que mudaram, sem precisar recarregar a tela inteira;
- Facilita muito a criação de aplicações web dinâmicas e de alta performance;
- É mantido pela Meta (Facebook) e amplamente utilizado no mercado.


## 2. Back-End
#### O que é uma API?
- Significa _Application Programming Interface_ (Interface de Programação de Aplicações);
- É a "ponte" de comunicação entre sistemas diferentes (ex: o Front-End conversando com o Back-End);
- O tipo mais comum na web é a **API REST**, que transmite dados no formato JSON;
- Permite integrar serviços externos, como meios de pagamento, mapas ou ferramentas de Inteligência Artificial.

#### O que é Node.js?
- Node.js NÃO é uma linguagem nem um framework, é um ambiente de execução para JavaScript;
- Permite rodar código JavaScript fora do navegador, principalmente no lado do servidor (Back-End);
- Utiliza o V8, o mesmo motor de alto desempenho do Google Chrome;
- Possibilita ser um desenvolvedor Full-Stack usando apenas uma linguagem (JavaScript);
- É extremamente leve, rápido e ideal para criar APIs REST e aplicações em tempo real.

#### O que é TypeScript?
- TypeScript é um _superset_ (superconjunto) do JavaScript criado pela Microsoft;
- Adiciona tipagem estática ao JavaScript (permite definir se uma variável é número, texto, objeto, etc.);
- Ajuda a capturar erros no código durante o desenvolvimento, antes mesmo de rodar o projeto;
- Todo código JavaScript válido também é um código TypeScript válido;
- É compilado (convertido) para JavaScript puro para poder rodar nos navegadores e no Node.js.
#### O que é Banco de Dados?
- É o sistema responsável por armazenar, organizar e consultar informações da aplicação de forma permanente;
- **Bancos Relacionais (SQL):** Organizam os dados em tabelas relacionais (Ex: PostgreSQL e MySQL);
- **Bancos Não-Relacionais (NoSQL):** Organizam os dados em documentos JSON flexíveis (Ex: MongoDB);
- No mercado Full-Stack, saber modelar dados e fazer consultas é indispensável.

#### O que é um ORM (Ex: Prisma)?
- Significa _Object-Relational Mapping_ (Mapeamento Objeto-Relacional);
- É uma ferramenta usada no Back-End que traduz a estrutura do banco de dados para código (JavaScript/TypeScript);
- Permite criar, ler, atualizar e deletar dados sem precisar escrever linhas puras de SQL;
- Aumenta a velocidade do desenvolvimento e reduz erros na manipulação dos dados.

## 3. Ferramentas e Versionamento
#### O que é Git e GitHub?
- **Git** é um sistema de controle de versão para acompanhar as alterações no código e trabalhar em equipe;
- **GitHub** é a plataforma onde hospedamos os projetos na nuvem usando o Git;
- Permitem voltar a versões antigas do código caso algo quebre;
- É o local onde você montará o seu portfólio prático de projetos para os recrutadores.

## 4. A importância de um editor de códigos
- Não precisamos de um editor para criar código de HTML e CSS;
- Porém, os editores são ótimas ferramentas para a programação;
- Nos ajudam com: estrutura de pastas, erros de sintaxe e highlight de sintaxe;
- Além de terem recursos extras, como terminal integrado e extensões que podem ser adicionadas;
- O meu preferido é o Visual Studio Code;
# Desafio MJV 

Seu desafio é montar partes de um sistema de loja virtual entre funcionalidades e tópicos demonstrados. **Sugerimos a escolha de uma ou duas funcionalidades para desenvolver.** 

Sugestões de funcionalidades a serem desenvolvidas:
- Menu de Categorias
- Lista de produtos
- Busca de produtos
- Detalhe de Produto
- Type-ahead (auto-complete) para busca de produtos
- Carrinho de compras
- Cadastro de usuário
- Login
- Página do usuário
- Lista de produtos (administrativo)
- Paginação
- Cadastro de produto

**Para desenvolvedores Frontend** é esperado uma aplicação SPA, pode-se mockar os dados no front para simular requests e estados de carregamento/erros.

**Para desenvolvedores Backend** pode-se fazer um sistema MVP ou uma API em GraphQL ou somente os endpoints REST(utilizar swagger se possível para documentar os endpoints) 

**Para desenvolvedores Full-stack**, é esperado uma aplicação MVC ou SPA consumindo um backend em GraphQL ou REST.

### Entregáveis

Envie um e-mail para alan.sa@mjv.com.br com o link do github do seu projeto. Crie um arquivo README.md e descreva as funcionalidades que foram desenvolvidas e instruções para rodar e acessar o projeto. 

Abaixo seguem os tópicos que gostariamos de ver de acordo com a stack usada. Queremos que nos mostre o seu melhor, então selecione as funcionalidades e tópicos que mais lhe darão oportunidade para mostrar os seus conhecimentos.

## Tópicos Comums (Front/Back): 

**Javascript**
- Demonstrar boa legibilidade de código
- Demonstrar domínio de lógica de programação
- Demonstrar uso de funcionalidades novas no Javascript (ex: async/wait, spread operators, arrow functions, template literals, etc)
- Demonstrar conhecimento de programação orientada a objetos
- Demonstrar conhecimento de programação funcional
- Utilização de estruturas imutáveis de dados
- Documentação com JSDocs
- Utilização de scripts npm
- Encadeamento de Promises

**Typescript**
- Demonstrar conhecimento e aplicação de Typescript (interfaces, tipos, união/intersecção de tipos, literais, etc) 
- Utilizar opções de compilação restritas (ex: strict: true)
- Utilizar opção de compilação *strictNullChecks* com uso de tipos null/undefined
- Utilização de type-guards
- Utilização de types auxiliares (ex: Required, Record, etc)
- Utilização de Generics

**RxJS**
- Demonstrar uso de operadores RxJS (ex. debounce de key strokes, retentativas de request) 
- Demonstrar uso de Subjects (ex: armazenamento de estado) 
- Demonstrar tratamento de erros


**Linter**
- Aplicar uso de linter p/ normalizar o estilo do projeto (ex: ESLint, TSLInt)

**Testes**
- Demonstrar conhecimento de testes unitários 
- Demonstrar conhecimento de mocks/stubs/spies

**Git**
- Demonstrar boa atomicidade nos commits (ex: único commit por funcionalidade ou bugfix)
- Demonstrar bom uso de mensagens de commit
- Utilizar algum formato padrão de mensagens de commit


## Tópicos de Frontend: 
- Criação de aplicação web 
- Uso de requisições HTTP 

**HTML/CSS**
- Layout Visual 
- Demonstrar boa aplicação de layout
- Demonstrar uso de layout responsível
- Demonstrar conhecimento de flex-box
- Demonstrar conhecimento de animações CSS
- Fazer uso de algum padrão de CSS (BEM, SMACSS) 
- Utilizar e fazer uso de recursos de algum framework CSS (ex: SCSS, Stylus, Less, etc)

**UX**: 
- Demonstrar boa navegabilidade
- Utilizar animações/elementos para guiar a experiência do usuário (ex: Indicadores de carregamento, transições de estado/página) 
- Configuração de Progressive-web-app 

**Angular**
- Demonstrar boas práticas de arquitetura 
- Utilizar rotas
- Utilizar módulos
- Utilizar módulos lazy-loaded
- Utilizar serviços
- Configuração e consumo de bibliotecas externas (ex. Angular Material)
- Demonstrar animações utilizando a API do Angular
- Utilizar biblioteca p/ gerenciamento de estado (ex: Apollo Client, NgRx, Akita, Angular-Redux, etc) 
- Tuning de performance de componentes
- Configuração de interceptador de request

**React**
- Demonstrar boas práticas de arquitetura 
- Utilização de functional components
- Utilização de React Hooks
- Utilização de Higher-Order-Components
- Utilização de pattern de container/presentational components
- Utilização de algum gerenciador de estado (Apollo Client, Redux, MobX, etc) 
- Integração com outras bibliotecas
- Lazy-load de componentes
- Utilização com Typescript 

## Tópicos de Backend:

**Padrão**
- Criação de aplicação backend 
- Uso de banco de dados relacional/não relacional 
- Script p/ estrutura do banco 
- Script p/ popular banco 
- Uso de Injeção de Dependência
- Utilização de JSON Web Tokens p/ autenticação 
- Validação de dados das requests
- Utilização de ORM

**NodeJS** 
- Utilização de middlewares
- Utilizar alguma ferramenta p/ auxilar o desenvolvimento (nodemon, node-dev, ts-node-dev, etc)

**GraphQL**
- Criação de endpoint GraphQL 
- Construir operações de Query
- Construir operações de Mutation
- Construir operações de Subscription
- Utilizar alguma união de tipo

**REST**
- Criação de endpoints REST p/ consumo do front
- Documentar a API com uso de Swagger 

**Docker**
- Configurar docker p/ as aplicações 

**C#**
- Uso de Enums
- Uso de Tuplas
- Uso de Generics
- Uso de estruturas de loop
- Uso de interfaces
- Uso de engine de template (Razor, Blazor, etc)
- Uso de Threads
- Uso de `using` em bloco
- Uso de dispose
- Uso de LINQ
- Uso de lambda-functions
- Uso de argumentos out/ref
- Modificadores de acesso (public/private etc)
- Uso de Task e async/await
- Uso de MVC
- Uso de annotations
- Uso de Collections

### Ferramentas

Imagens de placeholder - http://lorempixel.com/

### Boilerplates para GITPOD 

Faça o fork de algum desses projetos para começar o desafio! 

Frontend
[Angular](https://github.com/alanjhonnes/mjv-angular-gitpod)
[React](https://github.com/alanjhonnes/mjv-react-js-gitpod)
[React + TypeScript](https://github.com/alanjhonnes/mjv-react-ts-gitpod)
[Vue]() 
[Vue + TypeScript]()

BACKEND 
[Node.js express]()
[Node.js NestJs]()
[Java Springboot]()
[C#.Net Core]()
[PHP Symfony]()
[PHP Laravel]()

Todos os boilerplates possuem bancos MYSQL, PostgreSQL e MONGODB para serem usados conforme a preferência. 


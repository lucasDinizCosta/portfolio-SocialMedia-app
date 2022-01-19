# portfolio-SocialMedia-app

## Aplicativo desenvolvido originalmente por "JavaScript Mastery" em "Build and Deploy a Modern Full Stack Social Media App | FULL COURSE".
- Link: https://www.youtube.com/watch?v=1RHDhtbqo94

## Objetivo: Criar uma midia social online de fotos, similar ao Pinterest

## Ferramentas do projeto:
- HTML;
- CSS (Tailwind);
  - TailWind com React:
    - https://tailwindcss.com/docs/guides/create-react-app
- JavaScript;
- React
- Sanity (Sanity é a plataforma mais flexível para criar soluções de conteúdo orientadas por dados);
  - Link especial: https://www.sanity.io/javascriptmastery
- https://www.sanity.io/docs

## Organização do projeto:
- Frontend:
  - HTML;
  - CSS;
  - Javascript;
  - Node;
  - React;
    - React-Router-DOM: Utilizado para fazer o mapeamento das rotas do site
- Backend:
  - Javascript;
  - Node;
  - Sanity (Ferramenta que apresenta um banco de dados para imagens de maneira mais fácil);

## Comandos de destaque
- `sanity start` ==> inicializa o servidor local com a ferramenta sanity.
  - Lembrando de estar na pasta do backend que onde foi instalado o sanity.
- `sanity manage` ==> Gera um link no site com as informações do projeto no sanity.
  - Link: https://www.sanity.io/manage/personal/project/hgrsfd1v
- `npm start` ==> Inicializa o servidor NPM configurado, seja com React até outras APIs
- `npx create-react-app ./` ==> Cria um projeto React na diretório atual, CUIDADO, pois deve-se lembrar de estar na diretório `frontend`
- `npm install -D tailwindcss postcss autoprefixer` ==> Instala CSS Tailwind na pasta do projeto
- `npx tailwindcss init -p` ==> Inicializa o CSS Tailwind e gera os arquivos 'tailwind.config.js' e 'postcss.config.js'.
- `npm install @sanity/client @sanity/image-url react-google-login react-icons react-loader-spinner react-masonry-css react-router-dom uuid` ===> Os pacotes do Sanity são utilizados para conectar no backend. O do Google e para utilizar a autenticação de login, por fim, os pacotes React são permitir criar um grid mais bonito, contudo, o pacote `react-router-dom` é especial pois permitirá estabelecer as rotas de conexão e navegação na aplicação. `uuid` criará arquivos com identificador único.


## Anotações
- Codigo especial para o Sanity do plano gratuito:
  - `npm install -g @sanity/cli && sanity init --project-plan boosted-free-2021-12-08`
- Nome do projeto definido na instalação do Sanity: `shareme_jsm`
- Adicionar o primeiro user no sanity:
  - UserName: JSM
  - Image: https://jsmImage.com/ 
    - Essa URL nao existe, é só para criar o user.


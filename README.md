# Clone visual de uma plataforma de streaming

Clone visual não oficial de uma landing page de streaming, desenvolvido para praticar estruturação de páginas, responsividade, organização de estilos com Sass e automação de tarefas com Gulp.

Projeto criado exclusivamente para fins educacionais e de portfólio. Não possui vínculo, patrocínio ou aprovação da Disney ou de qualquer outra empresa representada.

## Demonstração

Acesse a versão online:

[Visualizar demonstração](https://disneyplus-clone-neon.vercel.app/)

## Sobre o projeto

Este projeto recria a experiência visual de uma página de assinatura de uma plataforma de streaming, com seções de planos, conteúdos, dispositivos compatíveis, download de filmes e séries e perguntas frequentes.

O foco principal foi praticar a construção de uma interface responsiva com identidade visual consistente, organização de componentes visuais e interações com JavaScript.

## Funcionalidades

- Cabeçalho com navegação e ações de assinatura e login;
- Seção principal com chamada para assinatura;
- Apresentação de planos e combinações de serviços;
- Abas interativas para alternar entre conteúdos;
- Seções de conteúdos em destaque;
- Apresentação de dispositivos compatíveis;
- Seção para download de filmes e séries;
- FAQ com perguntas expansíveis;
- Cabeçalho que altera sua visibilidade durante a rolagem;
- Layout responsivo para desktop, tablet e celular;
- Imagens específicas para diferentes tamanhos de tela;
- Estilos organizados com Sass;
- Minificação de CSS, JavaScript e imagens no processo de build.

## Tecnologias utilizadas

- HTML5
- Sass/SCSS
- JavaScript
- Gulp
- Node.js
- NPM
- Vercel

## Como funciona

### Abas de conteúdo

As abas Em breve, Mais populares e Mais no Star+ alternam as listas de conteúdos exibidas na página sem recarregar o navegador.

### FAQ

As perguntas frequentes funcionam como um accordion: ao clicar em uma pergunta, a resposta correspondente é aberta ou fechada.

### Cabeçalho durante a rolagem

O cabeçalho fica oculto durante a parte inicial da seção principal e volta a aparecer quando o usuário começa a navegar pelo restante da página.

## Estrutura do projeto

```text
disneyplus_clone/
├── assets/
│   └── fonts/
├── src/
│   ├── images/
│   ├── scripts/
│   │   └── main.js
│   └── styles/
│       └── main.scss
├── .gitignore
├── gulpfile.js
├── index.html
├── package.json
├── package-lock.json
└── README.md
```

A pasta dist é gerada pelo processo de build e contém os arquivos compilados para distribuição.

## Como executar o projeto localmente

### Pré-requisitos

Antes de começar, você precisa ter instalado:

- [Node.js](https://nodejs.org/)
- NPM, que normalmente é instalado junto com o Node.js

### Instalação

Clone este repositório:

```bash
git clone https://github.com/Marcela-prog/disneyplus_clone.git
```

Entre na pasta do projeto:

```bash
cd disneyplus_clone
```

Instale as dependências:

```bash
npm install
```

### Desenvolvimento

Para observar alterações nos arquivos Sass e JavaScript durante o desenvolvimento:

```bash
npm run dev
```

### Build de produção

Para compilar e otimizar os arquivos do projeto:

```bash
npm run build
```

O processo gera os arquivos compilados dentro da pasta dist.

## Aprendizados

Este projeto contribuiu para a prática de:

- Criação de landing pages para serviços digitais;
- Organização de uma interface com várias seções;
- Construção de abas e accordion com JavaScript;
- Controle de elementos durante a rolagem;
- Desenvolvimento responsivo para diferentes dispositivos;
- Uso de imagens específicas para desktop e celular;
- Organização de estilos com Sass;
- Automação de tarefas com Gulp;
- Minificação e preparação de arquivos para produção.

## Aviso sobre marcas e direitos autorais

Este é um clone visual não oficial criado para fins de estudo. Disney+, Star+, STARZPLAY, personagens, logotipos, imagens e demais elementos relacionados pertencem aos seus respectivos proprietários.

O projeto não oferece assinaturas, pagamentos, login real ou acesso a conteúdos protegidos.

## Autora

Desenvolvido por Marcela Nogueira.

- GitHub: [Marcela-prog](https://github.com/Marcela-prog)
- LinkedIn: [Marcela Nogueira](https://www.linkedin.com/in/marcela-nogueira-855272191)

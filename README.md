
# Projeto integrador - Irmãos do Joel

Projeto realizado na primeira turma do bootcamp de front-end do Mercado Livre Brasil pelo grupo Irmãos do Joel.

## 💻 Sobre o projeto
- O projeto Integrador é parte fundamental da metodologia da aprendizagem do IT Bootcamp e está presente em todas as edições. 
- No caso do IT Bootcamp - Front-End, ele é destinado à criação de uma aplicação Front-End completa, ao longo do período do Bootcamp, contemplando assim todos os temas abordados durantes os módulos de aprendizagem como embasamento técnico. 
- O PI é dividido em 4 sprints, cada uma com um conjunto de entregas específicas, para as quais, o grupo receberá o feedback e orientação para o aprimoramento do que for necessário.

## 🤖 Sprints IT Bootcamp - Front-End
| Número | Tema | Entrega |
| --- | ------------- | --- |
| [Sprint#1](https://drive.google.com/file/d/1Ghvx32Obw1ghiHmKtkriJZQ7gHFPAxNZ/view) | Páginas: Home, Lista e Detalhes | Realizar busca de produto que redirecione para uma nova página que traga como resultado um catálogo de produtos. Cada produto poderá ser visualizado em uma página de detalhes.
| [Sprint#2](https://drive.google.com/file/d/1kd2xUSreDc0QOJaugIVUkNujv-OPJBeb/view) | Paginação, Validações e Página Checkout   | Realizar uma demonstração da implementação do componente de paginação, quantidade de produtos por página. Validação de estoque e página de Checkout. 
| [Sprint#3](https://drive.google.com/file/d/1346Bbr3QtzUYI8WAEuL0jW5XVHbuvlzF/view)| Andes e refatoração lógica | Realizar uma demonstração da implementação dos componentes do Andes e refatoração das lógicas e atributos de todas as páginas do projeto. |
| [Sprint#4](https://drive.google.com/file/d/1Oaz3M4pf3kJ3iT021v9GE8Pahls9NAuA/view) | Testes e cobertura de teste| Realizar uma demonstração da cobertura de testes |
| [Encerramento]()| Apresentação final | Demonstração final baseada na apresentação da aplicação completa, cumprindo com os requisitos obrigatórios do projeto integrador. |

## 👩🏻‍🏫 Orientadora

- [Thalita Nunes](https://github.com/thalitameli)

## 🏆 Autores

- [Allany Filgueiras](https://github.com/Allanyfilgueirasdev)
- [Caio Magalhães](https://github.com/CaioMeli)
- [Ives Braga](https://github.com/ivBraga)
- [Luiz Sebastião](https://github.com/luiz-sebastiao-meli)
- [Patrick Sardou](https://github.com/psardou)
- [Sophia Fiama](https://github.com/sfiama)

## 🦾 Melhorias adicionadas individualmente
| Integrante | Feature | Função |
| --- | ------------- | --- |
| [@patrickSardou](https://github.com/psardou) | Especificações do produto | Especificações do produto na página de detalhes do produto 
| [@patrickSardou](https://github.com/psardou) | Spinner de carregamento | Spinner de carregamento a cada requisição 
| [@luizSebastiao](https://github.com/luiz-sebastiao-meli) | Breadcrumb de categorias | Breadcrumb para navegar entre as categorias da busca 
| [@luizSebastiao](https://github.com/luiz-sebastiao-meli) | Página de conclusão do checkout | Página para exibir informações de conclusão do checkout

## 📝 Planejamento 
- [Planejamento das Sprints](https://github.com/users/sfiama/projects/4/views/1)
- [Mocks - Design](https://www.figma.com/file/25PvBXIXW4206LogeCQguJ/Mocks?node-id=0%3A1)

## 👾 Requisitos do Projeto e Funcionalidades

- Pesquisa por produtos
- Listagem de produtos com paginação e filtros
- Página de detalhes do produto
- Página de resumo da compra
- Boas práticas de programação, código correto, completo, limpo e elegante.
- Boas práticas de acessibilidade
- Boas práticas de [WEB - SEO](https://www.quanzhanketang.com/website/web_search.html#:~:text=Search%20engine%20optimization%20(SEO)%20is,it%20is%20expected%20to%20receive.)
- Cobertura de código >= 80%.

## 🕸 Potenciais melhorias
- Pesquisa por produtos estar disponível nas páginas de listagem e detalhes;
- Disponibilidade para compra de Mix de produtos;
- Interação dinâmica com os filtros disponíveis na página de listagem; 
- Adição de seções extras: Banner, Descontos, Favoritos, Categorias populares, etc; 
- Exibir mais detalhes sobre o produto: Avaliações, Formas de pagamento, etc;

## 🧱 Build da aplicação

#### Instalação

- Instale o [Node](https://nodejs.org/es/), recomendamos a versão LTS 14
- Recomendamos o uso do [NVM](https://github.com/nvm-sh/nvm)
- Esteja conectado a VPN 

```bash
  git clone git@github.com:sfiama/fury_bootcamp-fe01-sfiama.git  
  cd fury_bootcamp-fe01-sfiama
  npm install
```

#### Build

- Dev

```bash
  npm run dev
```

## 🧩 Testes da aplicação

#### Testes de componentes
| Integrante | Componente | Tamanho |
| --- | ------------- | --- |
| [@sophiaFiama](https://github.com/sfiama) | ButtonComponent | pequeno |
| [@sophiaFiama](https://github.com/sfiama) | InputComponent | pequeno |
| [@sophiaFiama](https://github.com/sfiama) | DropdownComponent | pequeno |
| [@allanyFilgueiras](https://github.com/Allanyfilgueirasdev) | NotFoundComponent | pequeno |
| [@allanyFilgueiras](https://github.com/Allanyfilgueirasdev) | SearchComponent | pequeno |
| [@allanyFilgueiras](https://github.com/Allanyfilgueirasdev) | ProductListComponent | pequeno |
| [@patrickSardou](https://github.com/psardou) | PaginationComponent | pequeno |
| [@patrickSardou](https://github.com/psardou) | ProductCardComponent | médio |
| [@caioMagalhaes](https://github.com/CaioMeli) | CardCheckoutComponent | grande |
| [@ivesBraga](https://github.com/ivBraga) | ProductListFiltersComponent | grande |
| [@luizSebastiao](https://github.com/luiz-sebastiao-meli) | ProductDetailsComponent | grande |

#### Testando

- Testes Unitários

```bash
  npm run test:unit
```

## 🛠 Tecnologias e Ferramentas

- [Node](https://nodejs.org/es/)
- [NVM](https://github.com/nvm-sh/nvm)
- [React](https://es.reactjs.org/)
- [Nordic](https://nordic.adminml.com/)
- [Andes](https://furydocs.io/frontend-andes-ui/latest/guide/?path=/story/docs-development--page)
- [Fury](https://furydocs.io/docs/3.3.2/guide/#/lang-es/introduccion)
- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
- [Sass](https://sass-lang.com/)
- [npm](https://www.npmjs.com/)
- [ESlint](https://eslint.org/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [JavaScript](https://www.javascript.com/)
- [Figma](https://www.figma.com/)
- [Git](https://git-scm.com/)
- [Github](https://github.com/)
- [Jest](https://jestjs.io/pt-BR/docs/getting-started)
- [RTL](https://testing-library.com/docs/react-testing-library/intro/)

## 🎮 Demonstração

![Demonstração da pesquisa](https://media.giphy.com/media/wJeBLWIgrWLrdX5AWw/giphy.gif)
![Demonstração da página de listagem](https://media.giphy.com/media/Q7xmBrQmKzcpS78B7E/giphy.gif)
![Demonstração da página de detalhes](https://media.giphy.com/media/d3aEUbgW2KkCaI8Wko/giphy.gif)
![Demonstração da página de checkout](https://media.giphy.com/media/NBrz77DdxyRIeBQyzZ/giphy.gif)
![Demonstração da página de conclusão](https://media.giphy.com/media/Jtf4nHDXkidwOuKT2R/giphy.gif)
![Demonstração da página de not found](https://media.giphy.com/media/5YpUTvjBo8tTdafS7H/giphy.gif)

## ✅ Considerações finais

- O projeto foi fundamental para termos uma visão inicial das tecnologias utilizadas no Mercado Livre.
- Nos auxiliou a aprimorar nossas soft skills por meio do trabalho em equipe durante as sprints.
- Nos proporcionou um direcionamento com relação ao que estudar e aprimorar a partir de agora.
- Ficamos plenamente satisfeitos com o resultado obtido e com o conhecimento adquirido.
- Executamos com excelência, competimos em equipe para ganhar, demos nosso máximo e nos divertimos.

<p align="center">
  <img src="https://i.makeagif.com/media/1-08-2017/t4H-nD.gif" alt="Acabou" />
</p>

##  📃 Licença

© 2022 Mercado Libre

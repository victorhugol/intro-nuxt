# Introdução ao Nuxt


## O que é o Nuxt?

-   O framework Vue intuitivo( Texto da documentação )

## 1.0 - Benefícios de usar o Nuxt 

-   Modularidade : 
    -   O nuxt é baseado numa arquitetura modular. Pode ser escolhido mais de 50 modulos para fazer o desenvolvimento mais rápido. 

-   Renderização : 
    -   È possivel fazer aplicações SSR e também gerar páginas estáticas.



## 1.1 - Começando

Aqui temos a facilidade de usar o nosso gerenciador de pacotes favorito.

Para o yarn : 

```bash
    $ yarn create nuxt-app <project-name>
```

Para o npx : 

```bash
    $ npx create-nuxt-app <project-name>
```

Para o npm:

```bash
    $ npm init nuxt-app <project-name>
```

## 1.3 Rodando a primeira aplicação

Primeiro é preciso entrar na pasta com o nome do projeto e rodar
os seguintes scripts : 

No yarn : 

```bash
    yarn dev
```

No npm : 

```bash
    npm run dev
```


## 2.0 Roteamento


### 2.1 Criação de Rotas : 

O roteamento de páginas em Vuejs normalmente é feito com vue-router,
e para essas rotas funcionarem é preciso um arquivido de configuração.
No que tange ao Nuxt, esse trabalho de cofiguração do VueRouter é abstraído,
precisando somente adicionar um arquivo ****.vue*** na pasta *** pages *** gerada pelo Nuxt.

### 2.2 Navegação : 

Para linkar rotas da própria aplicação, só usar a tag
`<NuxtLink>` : 

```html

    <template>
        <NuxtLink to="<nome_da_rota>">Conteudo</NuxtLink>
    </template>

```

Para linkar a paginas fora da aplicação, usar a tag `<a>`:

```html

    <template>
        <a href="https://google.com"> Conteudo </NuxtLink>
    </template>

```


## 3.0 Estrutura dos diretórios


### 3.1 Diretório : pages


Este diretório é responsavel por armazenar as views e rotas da aplicação,
como ja visto anteriormente,  o Nuxt vai usar todos *** .vue *** para criar router
da aplicação.


### 3.2 Diretório : components

Este é o repositório onde vai ser armazenado os componentes Vuejs que vão ser usados dentro da *** pages ***

Depois de criar o componente, a importanção deste dentro da página não precisa ser feita de maneira manual, o Nuxt é responsável por fazer esse trabalho, usando
um *** auto import ***





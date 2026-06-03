# Project-Task_Manager_App

Gerenciador de tarefas desenvolvido com HTML, CSS e JavaScript.

O objetivo deste projeto foi praticar conceitos fundamentais de front-end com JavaScript puro, incluindo manipulação do DOM, controle de estado, consumo de API, filtros, busca, modularização de arquivos e persistência de dados no navegador com LocalStorage.

## Tecnologias

### Front-end

* HTML
* CSS
* JavaScript

### Ferramentas

* Git
* GitHub
* VS Code

## Funcionalidades

* Adicionar tarefas
* Editar tarefas
* Excluir tarefas
* Filtrar tarefas por status
* Buscar tarefas pelo título
* Renderizar tarefas dinamicamente na tela
* Consumir dados iniciais de uma API externa
* Persistir tarefas no LocalStorage
* Atualizar a interface com base no estado da aplicação

## Estrutura do projeto

```txt
Task_Manager_App/
├── index.html
├── assets/
│   └── imgs/
├── js/
│   ├── main.js
│   ├── render.js
│   ├── task.js
│   ├── filter.js
│   └── state.js
├── style.css
│   
└── README.md
```

## Como funciona

A aplicação utiliza JavaScript puro para controlar o estado das tarefas, renderizar os dados na interface e reagir às interações do usuário.

Os dados iniciais são buscados da API JSONPlaceholder. Depois disso, as tarefas passam a ser manipuladas localmente pela aplicação e salvas no LocalStorage do navegador.

Fonte inicial dos dados:

```txt
https://jsonplaceholder.typicode.com/todos
```

Fluxo principal da aplicação:

```txt
Aplicação é carregada
→ JavaScript busca dados iniciais da API
→ tarefas são armazenadas no estado da aplicação
→ a interface é renderizada dinamicamente
→ usuário adiciona, edita, remove, filtra ou busca tarefas
→ estado é atualizado
→ dados são salvos no LocalStorage
→ interface é renderizada novamente
```

A aplicação foi organizada em arquivos separados para dividir melhor as responsabilidades, como controle de estado, renderização, filtros e manipulação das tarefas.

## Persistência de dados

O projeto utiliza LocalStorage para salvar as tarefas no navegador.

Isso permite que as alterações feitas pelo usuário sejam mantidas mesmo após atualizar ou fechar a página.

## Como rodar localmente

### Pré-requisitos

* Git
* Navegador instalado

### Clonar o repositório

```bash
git clone https://github.com/Pyrad-Time/Task_Manager_App.git
cd Task_Manager_App
```

### Abrir o projeto

Abra o arquivo `index.html` diretamente no navegador.

Também é possível usar a extensão **Live Server** no VS Code para executar o projeto localmente.

## Preview

<img width="605" height="634" alt="ProjectPreview-Task_Manager_App" src="https://github.com/user-attachments/assets/cbf820bc-38df-4ade-b2e1-8ae50cfe0576" />

## Aprendizados

Durante o desenvolvimento deste projeto, pratiquei:

* Manipulação do DOM
* Captura e tratamento de eventos
* Controle de estado com JavaScript
* Uso de métodos de array como `map`, `filter` e `includes`
* Busca de dados com `fetch`
* Consumo de API externa
* Renderização dinâmica
* Filtros por status
* Busca por texto
* Persistência de dados com LocalStorage
* Separação de responsabilidades em módulos
* Organização do fluxo de uma aplicação front-end

## Status

MVP finalizado.

O projeto permite adicionar, editar, excluir, buscar e filtrar tarefas utilizando JavaScript puro, consumo de API externa e persistência local no navegador.

## Possíveis melhorias

* Melhorar a experiência visual da edição de tarefas
* Adicionar tratamento de erro para falhas na API
* Melhorar a responsividade
* Criar mensagens visuais para ações do usuário
* Recriar o projeto futuramente com React

## Autor

Desenvolvido por Marcos Vinicius de Azevedo.

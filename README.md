# 🎴👨‍💻 Clone Pipefy

## 📝 Descrição
O projeto é um clone do Pipefy, uma aplicação para gerenciamento de tarefas, com o objetivo de permitir que o usuário crie e organize listas de tarefas em diferentes categorias apenas arrastando e soltando.

## 🔗 Acesse o Projeto
Clique [aqui](https://drag-in-drop-raiz.vercel.app/) para acessar o projeto.

## 💻 Uso
A aplicação permite que o usuário organize e gerencie tarefas em diferentes listas.

## 📋 Índice
- [Instalação](#-instalação)
- [Execução](#-execução)
- [Ferramentas](#%EF%B8%8F-ferramentas)
- [Conceitos Aplicados](#-conceitos-aplicados)
- [Explicação Detalhada do Código](#-explicação-detalhada-do-código)

## 🔧 Instalação
Para instalar o projeto, basta clonar o repositório em sua máquina local e instalar as dependências. Para isso, execute os seguintes comandos no terminal:
</br>

```git
git clone https://github.com/M0rona/RocketFy.git
cd RocketFy
npm install
```

## 🚀 Execução
Para executar o projeto, execute o seguinte comando no terminal:
```node
npm start
```

## 🛠️ Ferramentas
- ReactJS
- Immer
- React-DnD

## 🧩 Conceitos Aplicados
* React Hooks (useState, useContext, useRef)
* Imutabilidade
* Drag and Drop

## 🔎 Explicação Detalhada do Código
O projeto é composto por três componentes principais: Board, List e Card. O componente Board é responsável por gerenciar o estado das listas e tarefas, o componente List é responsável por exibir as listas e o componente Card é responsável por exibir as tarefas.

O componente Board utiliza o hook useState para gerenciar o estado das listas e tarefas, e o hook useContext para fornecer o contexto para os componentes filhos. Ele também utiliza a biblioteca Immer para permitir que o estado seja atualizado de forma imutável, o que ajuda a evitar bugs e a tornar o código mais fácil de entender e manter. O componente Board também utiliza a função loadLists para carregar as listas e tarefas da API.

O componente List recebe as propriedades das listas e exibe as tarefas correspondentes, utilizando o componente Card. Ele também permite que o usuário crie novas tarefas na lista, clicando no botão de adicionar.

O componente Card exibe as informações da tarefa, como o título e a descrição. Ele também permite que o usuário mova a tarefa de uma lista para outra, utilizando a biblioteca React-DnD para arrastar e soltar.

No geral, o código é organizado de forma modular, com cada componente responsável por uma parte específica da aplicação. Isso torna o código mais fácil de entender, manter e testar.

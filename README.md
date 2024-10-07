# Lista de Tarefas

Este é um projeto simples de **Lista de Tarefas** desenvolvido para praticar e consolidar os conceitos básicos de **JavaScript**. O projeto permite que os usuários adicionem e removam tarefas, além de salvar os dados no **LocalStorage** para que as tarefas sejam persistidas mesmo após recarregar a página.

## Funcionalidades

- **Adicionar tarefas**: O usuário pode inserir uma nova tarefa na lista.
- **Remover tarefas**: As tarefas podem ser excluídas da lista.
- **Persistência de dados**: As tarefas são salvas no navegador usando o **LocalStorage**, garantindo que a lista seja mantida após recarregar a página.

## Tecnologias Utilizadas

- **HTML**: Estrutura da página.
- **CSS**: Estilização básica da interface.
- **JavaScript**: Manipulação do DOM e lógica de adição/remoção de tarefas.
- **LocalStorage**: Para persistência de dados no navegador.

## Como Funciona

1. **Adicionar tarefa**: Insira o nome de uma tarefa no campo de texto e clique no botão "Adicionar".
2. **Remover tarefa**: Clique no link "Excluir" ao lado de qualquer tarefa para removê-la da lista.
3. **Salvamento automático**: Toda alteração na lista é automaticamente salva no **LocalStorage**, garantindo que as tarefas sejam mantidas entre as sessões.

## Conceitos Aprendidos

- **Manipulação do DOM**: Criação e remoção de elementos HTML com `document.createElement()`, `appendChild()`, e `innerHTML`.
- **Eventos**: Captura de eventos de clique através de `addEventListener()` e manipulação dinâmica de elementos com funções de callback.
- **Armazenamento Local**: Uso de `localStorage` para salvar e recuperar dados da lista de tarefas em formato JSON.
- **Manipulação de Arrays**: Adição e remoção de itens utilizando métodos como `push()` e `splice()`.

## Estrutura de Arquivos

```bash
lista-de-tarefas/
│
├── index.html         # Arquivo HTML principal
├── style.css          # Arquivo de estilos
└── script.js          # Lógica do JavaScript para adicionar/remover tarefas

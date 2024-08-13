# Gerenciador de Lista com LocalStorage
Este projeto é um simples gerenciador de lista de tarefas que utiliza o localStorage do navegador para armazenar e gerenciar itens de uma lista. Ele permite adicionar, visualizar e limpar itens da lista.

## Funcionalidades
Salvar Item: Adiciona um item à lista armazenada no localStorage.
Visualizar Lista: Exibe todos os itens armazenados na lista.
Limpar Lista: Remove todos os itens da lista e limpa a exibição.
Estrutura do Código
O código é composto por três funções principais:

## salvarItem()
Esta função é responsável por:

Obter o valor do input com o ID item.
Adicionar o item à lista armazenada no localStorage.
Limpar o campo de entrada após a adição do item.

## visualizarLista()
Esta função realiza as seguintes ações:

Recupera a lista armazenada no localStorage.
Cria uma lista HTML (<ul>) e adiciona cada item da lista como um <li>.
Atualiza a exibição da lista na página HTML.

## limparLista()
Esta função:

Remove a lista do localStorage.
Limpa a exibição da lista na página HTML.
Como Usar
Adicionar Itens:

Digite o item no campo de entrada com o ID item.
Chame a função salvarItem() para adicionar o item à lista.
Visualizar Itens:

Chame a função visualizarLista() para atualizar e exibir a lista atual.
Limpar Lista:

Chame a função limparLista() para remover todos os itens da lista e limpar a exibição.

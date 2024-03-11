# Conceitos de Redux

- É uma forma de gerenciar os estados globalmente.

## Problema a ser resolvido

- O Redux ajuda a resolver o problema de PROP DRILLING, que é quando componentes recebem estados por props que não vão ser utilizados; e isso em um projeto de larga escala pode ser uma enorme dor de cabeça.

- O Redux veio para ajudar nisso; é uma forma de gerenciar estados globalmente e utilizar e importar os estados onde vão ser de fato utilizados.
Entendendo o Redux: Reducer, State Global, UseSelector, Actions, Dispatches (useDispatch)

### Reducer

- É o local onde vai ser armazenado todos os estados globais.

### State Global

- São todos os estados que podem ser usados em qualquer lugar da nossa aplicação.

### UseSelector

- É o hook que vamos utilizar para acessar os estados presentes no Reducer.

### UseDispatch

- É o hook responsável por dispachar/acionar actions.

### Actions

- É como fazemos modificações nos reducers de nossa aplicação.

É um Objeto que tem os seguintes elementos

type: "users/login" => Serve para identificar a ação no reducer.
payload: {name, email} => São os dados que vão ser alterados.

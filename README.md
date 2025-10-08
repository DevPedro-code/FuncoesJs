# FuncoesJs
# Funções em Javascrit:
Tutorial das 3 tipos de funções em Javascript

# O que é uma função?

A função é um bloco de código que pode ser executado em uma tarefa específica, ela ajuda a organizar o código e deixa ela mais limpa.


# Arrow Function
Regras:
As funções arrow em JavaScript usam a sintaxe => em vez da palavra-chave function, e devem ser atribuídas a uma variável ou constante. E para retornar um  valor, utiliza-se a instrução return dentro do corpo da função.

Código:
```js
let subtracao = (a,b) => {
  return a - b;
}
subtracao(13,4); //a saida é: 9
```
Para declarar esse tipo de função, você deve substituir a palavra chave (function) pela sintaxe de atribuição a uma constante ou variável. Você precisa usar a seta (=>) entre os parâmetros.


# Declaration Function

Regras: Esse tipo de função precisa ter o uso da palavra chave (function), seguida por um nome de função, parênteses () que podem conter parâmetros e chaves {} que delimitam o corpo da função. E para retornar um  valor, utiliza-se a instrução return dentro do corpo da função. 

Código:
```js
function soma (a,b){
  return a + b;
}
soma(13,24); //a saída é: 37
```
Para declarar essa função usa a palavra (function) em seguida por um nome da função, parenteses () para os parâmetros e chaves {} para o corpo da função.

# Expression Function

Regras: A sintaxe com a palavra-chave function, um nome opcional, uma lista de parâmetros e um corpo de código entre chaves {} para o corpo da função. Essa função ela pode ser sem nome e atribuídas em varáveis, permitindo que sejam usadas como qualquer outro objeto na linguagem.

Código:
```js
let multiplicacao = function (a,b){
return a * b;
}
multiplicacao(5,4); //a saída é: 20
```

Para declara essa função você atribui um bloco de função a uma variável (let) (var) (const). O nome da função é opicional e também pode ser omitido para criar função sem nome, que são chamadas usando o nome da variável.



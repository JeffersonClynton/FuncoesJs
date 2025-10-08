# FuncoesJs
Primeira atividade de LS


1. Declaration Function

Você pode chamar a função antes dela ser declarada, a função pode ficar abaixo da chamada.
Ela é boa para funções global.

Ex.:

```js
function somar (a,b){
  return a + b;
}
```
Você pode colocar a chamada da função tanto em cima quanto abaixo dela.

//-------------------------------------------------------------------------------------------

2. Function Expression

A função é guardada em uma variável.
É boa para você controlar melhor dentro de um escopo.

Ex.:

```js
let somar = function (a,b){
  return a + b;
}
```
Aqui como tem variável você precisa usar as palavras-chaves de declaração de variáveis.
A chamada da função deve ficar abaixo dela.

//------------------------------------------------------------------------------------------

3. Arrow Function

Tem uma sintaxe mais curta.

Ex.:
```js
let somar = (a,b) => a + b;
```
Como pode ver ela tem um "return" implícito.
Mas quando tem mais de uma expressão, precisa usar {} e do "return".

Ex.:
```js
let somar = (a,b) => {
  let result = a + b;
  return result;
}
```

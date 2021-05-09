<!--
Antes de publicar a issue, lembre-se de clicar na aba "Preview", para visualizar se a formatação está correta =)
-->

# Constantes, variáveis e comentários - Aula 01-06

## Variáveis - let

As variáveis armazenam valores (string, número etc). É como se fossem containeres para um dado/informação.

Podemos declarar uma variável das seguintes formas:

```js
let age = 27;

let currentYear = 2021;

console.log(age, currentYear); // 27, 2021
```


O símbolo de `=` serve como um operador de atribuição de valor. Para atribuírmos um valor diferente à uma variável, podemos fazer da seguinte maneira.

```js
age = 29;

console.log(age) // 29
```


O segundo console após a reatribuição de valor imprime o novo valor.

## Constantes - const

Usaremos a palavra chave `const` quando quisermos que a variável criada não sofra alteração em seu valor, ou seja, seja constante.

```js
const points = 100

points = 101

console.log(points) // retorna um erro
```

## Regras para nomear variáveis
- não pode conter espaços
- usar padrão camel case
- não pode começar com número
- não pode ser palavras reservadas
- dê nomes significativos e claros que revelam uma intenção

## Comentários

- podem ser de uma linha

```
// comentário de uma linha
```

- pode ter múltiplas linhas

```
/*
comentário de 
múltiplas linhas
*/
```


<!-- Escreva/insira as imagens após essa linha -->



<!-- Não apague daqui para baixo! -->
@Roger-Melo

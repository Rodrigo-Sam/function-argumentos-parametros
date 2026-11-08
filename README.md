# Function Argumentos / Parâmetros

Exercício de fixação para Funções em JavaScript, feito na aula.

## O que é o projeto?

Uma página que explica o que são argumentos/parâmetros e mostra na prática como eles funcionam, fazendo as 4 operações matemáticas com 2 valores.

## O que eu aprendi?

- O que é uma Function em JavaScript
- O que são Argumentos e Parâmetros
- Como passar valores para uma função quando ela é chamada
- Como usar esses valores dentro da função para fazer cálculos
- Como usar `alert()` para mostrar o resultado
- Como ligar uma função a um botão com `onclick`

## Como funciona?

1. Abre a página
2. Clica no botão **Calcular**
3. A função `sun(value, value2)` é chamada com os valores `10` e `20`
4. Aparecem 4 alerts em sequência:

- `10 + 20 = 30`
- `10 - 20 = -10`
- `10 * 20 = 200`
- `10 / 20 = 0.5`

## Código principal

```js
function sun(value, value2) {
    alert(value + " + " + value2 + " = " + (value + value2));
    alert(value + " - " + value2 + " = " + (value - value2));
    alert(value + " * " + value2 + " = " + (value * value2));
    alert(value + " / " + value2 + " = " + (value / value2));
}

# Projeto de Verificação de Números Par e Ímpar
[Go to English Version](#par-and-odd-numbers-check-project)

## Objetivo
Este projeto tem o intuito de ser para aprender sobre como se faz um programa que: recebe um número inteiro digitado, verifica se ele é ímpar ou par e retorna para quem digitou se é ímpar ou par.

## Finalidade
Serviu como intuito para:
- Aprender sobre operadores `%` e `?` em JavaScript.

## Descrição do Projeto + Requisitos do projeto
O código começa pedindo para ao usuário digitar um número, e o código analisa se o número digitado é ímpar ou par.

Como é um código feito em JavaScript e precisa ter um input perguntando e pedindo um número, precisei rodá-lo em um arquivo HTML, através da tag `<script>` e utilizando um LocalHost, como o Five Server ou LiveServer.
### Sobre o Código
- Utilizei o padrão de boas práticas em declaração de identificadores (variáveis, constantes) e com isso utilizei `let` ao invés de `var`.
- As variáveis estão com nome `num` que é a que recebe o número digitado, e `result` que é a que faz a lógica do programa funcionar e verifica se o número é ímpar ou par.
- O `parseInt` é usado para converter o valor fornecido pelo prompt em um número inteiro. Este número é armazenado na variável `num`.
### Lógica do Código
O operador de módulo `%` (na variável `result`) é usado para calcular o resto da divisão de `num` por 2. Se o resto for igual a 0, significa que o número é divisível por 2 e, portanto, é par. Caso contrário, o número é ímpar. O operador ternário `?` é usado para verificar esta condição. Se a condição for verdadeira (o número é par), a variável `result` recebe a string "<span style='color: green'>Par</span>"; caso contrário, recebe a string <font color="green">Ímpar.

O operador ternário `? :` é utilizado para fazer uma escolha entre duas opções com base em uma condição específica. A condição é verificada pelo operador de módulo `%`, que calcula o resto da divisão de `num` por 2. Se o resto for igual a 0, isso indica que o número é par, e a primeira opção é selecionada. Caso contrário, se o resto não for zero, o número é ímpar, e a segunda opção é escolhida.

A condição específica é `num % 2 === 0`, onde `num` representa o número digitado pelo usuário. Se essa condição for verdadeira, o número é considerado par; caso contrário, é ímpar.

# Par and Odd Numbers Check Project
<a name="par-and-odd-numbers-check-project"></a>

## Objective
This project aims to be a learning experience on how to create a program that: receives a typed integer, checks if it is odd or even, and returns to the user whether it is odd or even.

## Purpose
It served as a purpose to:
- Learn about the `%` and `?` operators in JavaScript.

## Project Description + Project Requirements
The code starts by asking the user to type a number, and it analyzes if the typed number is odd or even.

As it is JavaScript code and requires an input asking for a number, it needed to be run in an HTML file, using the `<script>` tag and a LocalHost like Five Server or LiveServer.
### About the Code
- I used the standard best practices in declaring identifiers (variables, constants), and with that, I used `let` instead of `var`.
- The variables are named `num` which receives the typed number, and `result` which performs the program's logic and checks if the number is odd or even.
- `parseInt` is used to convert the value provided by the prompt into an integer. This number is stored in the `num` variable.
### Code Logic
The modulo operator `%` (in the `result` variable) is used to calculate the remainder of `num` divided by 2. If the remainder is equal to 0, it means the number is divisible by 2 and therefore even. Otherwise, the number is odd. The ternary operator `?` is used to check this condition. If the condition is true (the number is even), the `result` variable receives the string "<span style='color: green'>Even</span>"; otherwise, it receives the string "<span style='color: red'>Odd</span>".

The ternary operator `? :` is used to make a choice between two options based on a specific condition. The condition is checked by the modulo operator `%`, which calculates the remainder of `num` divided by 2. If the remainder is equal to 0, it indicates that the number is even, and the first option is selected. Otherwise, if the remainder is not zero, the number is odd, and the second option is chosen.

The specific condition is `num % 2 === 0`, where `num` represents the number typed by the user. If this condition is true, the number is considered even; otherwise, it is odd.

The modulo operator `%` (in the `result` variable) is used to calculate the remainder of `num` divided by 2. If the remainder is equal to 0, it means the number is divisible by 2 and therefore even. Otherwise, the number is odd. The ternary operator `?` is used to check this condition. If the condition is true (the number is even), the `result` variable receives the string "<span style='color: green'>Even</span>"; otherwise, it receives the string "<span style='color: red'>Odd</span>".

The ternary operator `? :` is used to make a choice between two options based on a specific condition. The condition is checked by the modulo operator `%`, which calculates the remainder of `num` divided by 2. If the remainder is equal to 0, it indicates that the number is even, and the first option is selected. Otherwise, if the remainder is not zero, the number is odd, and the second option is chosen.

The specific condition is `num % 2 === 0`, where `num` represents the number typed by the user. If this condition is true, the number is considered even; otherwise, it is odd.

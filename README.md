# Calculadora Simples

Este é um código para uma calculadora simples feita em JavaScript. Abaixo está uma breve explicação de cada parte do código:

1. `let runningTotal = 0;`:
    - Variável para armazenar o resultado da operação atual.

2. `let buffer = "0";`:
    - Buffer para armazenar os números e símbolos digitados pelo usuário.

3. `let previousOperator;`:
    - Variável para armazenar o operador anterior.

4. `const screen = document.querySelector('.screen');`:
    - Seleciona o elemento da tela da calculadora onde os números e resultados são exibidos.

5. `function buttonClick(value)`:
    - Função que é chamada quando um botão da calculadora é clicado. Ela determina se o valor clicado é um número ou um símbolo e chama a função apropriada para lidar com isso.

6. `function handleSymbol(symbol)`:
    - Função para lidar com os símbolos clicados (como 'C' para limpar, '=' para calcular, '←' para apagar último dígito e operadores aritméticos).

7. `function handleMath(symbol)`:
    - Função para lidar com os operadores aritméticos clicados (como '+', '−', '×', '÷').

8. `function flushOperation(intBuffer)`:
    - Função para executar a operação aritmética com base no operador anterior.

9. `function handleNumber(numberString)`:
    - Função para lidar com a entrada de números.

10. `function init()`:
    - Função de inicialização que adiciona um ouvinte de evento de clique aos botões da calculadora para chamar a função `buttonClick` quando um botão é clicado.

11. `init();`:
    - Chama a função `init()` para iniciar a calculadora quando a página é carregada.

Este código cria uma calculadora básica que pode realizar operações aritméticas simples.

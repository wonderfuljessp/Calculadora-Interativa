### NOME DO PROJETO
Calculadora Interativa

### DESCRIÇÃO
Uma calculadora modular capaz de realizar operações básicas de adição, subtração, multiplicação e divisão com números decimais.

### LÓGICA UTILIZADA
A estrutura `switch/case` foi escolhida por ser mais prática e direta que um longo encadeamento de `if/else` para criar o menu de opções. Além disso, apliquei uma trava de segurança com a condição `if(b != 0)` no caso da divisão, garantindo que o divisor seja diferente de zero para evitar erros matemáticos.

### COMO EXECUTAR
Para executar este programa na sua máquina, você deve compilá-lo no terminal usando o comando:
`gcc calculadora.c -o calculadora`
Por fim, execute-o com o comando:
`calculadora.exe` (no Windows) ou `./calculadora` (no Linux/Mac).

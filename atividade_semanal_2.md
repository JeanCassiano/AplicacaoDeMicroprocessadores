### Questão 6

Instrução CISC:

Mais instruções disponíveis: CISC, ele possui um conjunto de instruções mais amplo e complexo.

Programas menores: CISC visto que é necessário um menor número de instruções necessárias para realizar uma tarefa, resultando em programas menores).

Tempo de execução das instruções depende da frequência do clock: CISC.

Processamento de cada instrução é mais lento: CISC, as instruções possuem durações diferentes.


Instrução RISC:

Os programas são mais complexos: RISC, visto que menos instruções disponíveis resultam em programas mais complexos.

A maioria das instruções tem a mesma duração: RISC, já que as instruções são simples e geralmente executadas em um ciclo de clock, exceto as de "salto".

Microcontroladores PIC, AVR, ARM: RISC.

Utiliza menos espaço na memória de programa: RISC, devido à maior densidade de instruções, menos espaço é necessário.



### Questão 7

Trata-se de uma arquitetura Von Neumann, visto que a CPU se comunica tanto com a memória de programa (FLASH) quanto com a memória de dados (RAM) através de um único barramento. Isso é indicado pelo "BUS CONTROL" que conecta tanto a memória RAM quanto a memória FLASH à CPU.
O diagrama mostra um bloco denominado "4 I/O PORTS", indicando que existem 4 portas de entrada/saída (P0, P1, P2, P3) que são bidirecionais.
Cada uma dessas 4 portas I/O geralmente possui 8 bits, dado que as portas em microcontroladores são normalmente endereçadas por byte. Assim, se cada porta possui 8 pinos, ao todo seriam 32 pinos (4 portas x 8 bits/pinos por porta) que podem ser endereçados de forma individual.
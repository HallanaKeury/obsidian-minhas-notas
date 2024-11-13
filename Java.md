
🔺O que é Java?  
  
📍 Linguagem de programação  
📍Plataforma de desenvolvimento e execução  
-Bibliotecas(API)  
-Ambientes de execução  
  
🔺Sobre Linguagem Compilada, interpretada e híbrida  
  
🔹Linguagem compilada: O código é traduzido para código de máquina de uma vez, antes de ser executado, e geralmente tem performance melhor.  
🔹Linguagem interpretada: O código é interpretado e executado linha por linha, durante a execução, sendo mais flexível, mas menos eficiente.  
🔹Linguagem híbrida: Algumas linguagens podem combinar os dois métodos, sendo compiladas para um código intermediário que depois é interpretado por uma máquina virtual (VM). Um exemplo é o Java, que é compilado para bytecode (código intermediário) e executado pela Java Virtual Machine (JVM).  
  
🔺Tipos primitivos de dados em Java

| Descrição                        | Tipo   | Tamanho   | Valores                                           | Valor Padrão |
|----------------------------------|--------|-----------|---------------------------------------------------|--------------|
| Tipos numéricos inteiros         |        |           |                                                   |              |
| Byte                             | byte   | 8 bits    | -128 a 127                                        | 0            |
| Short                            | short  | 16 bits   | -32768 a 32767                                    | 0            |
| Int                              | int    | 32 bits   | -2147483648 a 2147483647                          | 0            |
| Long                             | long   | 64 bits   | -9223372036854770000 a 9223372036854770000        | 0L           |
| Tipos numéricos com ponto flutuante |       |           |                                                   |              |
| Float                            | float  | 32 bits   | -1,4024E-37 a 3,4028E+38                          | 0.0f         |
| Double                           | double | 64 bits   | -4,94E-307 a 1,79E+308                            | 0.0          |
| Um caractere Unicode             | char   | 16 bits   | '\u0000' a '\uFFFF'                               | '\u0000'     |
| Valor verdade                    | boolean| 1 bit     | {false, true}                                     | false        |


  
🔺BITS  
>Um bit pode armazenar 2 valores possíveis (0 ou 1)  
Cada bit = 2 possibilidades  
8 bits:  
2 x 2 x 2 x 2 x 2 x 2 x 2 x 2 = 28 = 256 possibilidades  
  
  
🔺TIPOS USANDO O PRINTF  
> Regra geral para printf:  
"TEXTO1 %f TEXTO2 %f TEXTO3", variavel1, variavel2  

🔺Formatação de Especificadores em Java

| Especificador | Descrição     | Tipo          |
|---------------|---------------|---------------|
| %f            | Ponto flutuante | float        |
| %d            | Inteiro       | int           |
| %s            | Texto         | String        |
| %n            | Quebra de linha | newline      |


🔺Casting  
>É a conversão explícita de um tipo para outro.É necessário quando o compilador não é capaz de “adivinhar” que o resultado de uma expressão deve ser de outro tipo.  
resultado = (double) a / b;



🔺Operadores de atribuição cumulativa

| Operador | Explicação     | Equivalente |
| -------- | -------------- | ----------- |
| `a += b` | Adição         | `a = a + b` |
| `a -= b` | Subtração      | `a = a - b` |
| `a *= b` | Multiplicação  | `a = a * b` |
| `a /= b` | Divisão        | `a = a / b` |
| `a %= b` | Módulo (resto) | `a = a % b` |







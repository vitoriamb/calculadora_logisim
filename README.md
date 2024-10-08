# 


## Interface Principal
![interface-principal](interface-principal.gif)

Calculadora com Circuitos Combinacionais



## Introdução


O relatório apresenta os detalhes de construção do projeto de uma calculadora digital capaz de realizar operações entre dois números hexadecimais de um único dígito, variando de 0 a F. O sistema foi projetado para explorar circuitos lógicos combinacionais. Este é um projeto da cadeira de Circuitos Digitais, desenvolvido por estudantes do curso de Ciência da Computação da Universidade Federal do Cariri (UFCA).

## Objetivo

O objetivo do projeto é criar uma calculadora digital intuitiva para inserir dois números hexadecimais por meio de LEDs e displays de 7 segmentos, permitindo a realização de soma, subtração, multiplicação e possuindo um circuito comparador. Também tem o objetivo de implementar os conteúdos da cadeira de Circuitos Digitais.




## Componentes utilizados




### **Multiplexador 4x1**

O circuito multiplexador possui 4 entradas, 1 saída e 2 bits de seleção. Sua função principal é receber múltiplas entradas e, com base nos bits de seleção, escolher uma delas para transferir à saída.


![Circuito multiplexador](./multiplexador.gif)


### **Circuito Somador**

O circuito somador permite a realização de operações de adição sendo essencial para a conclusão do projeto.

1 passo: implementar um meio somador de 2 entradas a e b usando portas lógicas

![Circuito meio somador](./meio%20somador.gif)

2 passo: somador completo*
Utiliza dois meio somadores e uma porta OR, com 3 entradas (a,b,c) e duas saídas (S e Ci) 



![Circuito somador completo](./somador%20completo.gif)


3 passo: somador de 4 Bits*

Utiliza o meio somador e 4 somadores completos sendo que o meio somador já vai estar presente.

![circuito somador](Somador.gif)



### **Circuito Comparador de Magnitude**


O comparador de magnitude é utilizado para comparar dois números binários e determinar a relação entre eles. Ele verifica se um número é maior, menor ou igual ao outro. O comparador possui duas entradas com a mesma quantidade de bit onde vai indicar se A>B, A=B, A<B para suas entradas a e b de n bits.

se os números forem iguais A=B=1 e os outros são 0.
se A>B=1 e os outros são 0 
se A<B=1 e os outros 0


![circuito comparador](comparador.gif)


 ### **Circuito Subtrator**

O subtrador foi feito com meio somadores e somadores completos, no modelo somador/subtrador controlado, porém com uma alteração em sua estrutura para realizar somente a operação de subtração.

![circuito subtrator](subtrator.gif)

 
 ### **Circuito Decodificador Inverso**

O Decodificador Inverso foi feito baseado no decodificador para display de 7 segmentos pois é basicamente o inverso do mesmo. Foi utilizado a tabela verdade, mas ao invés do mapa de Karnaugh, foi utilizado a soma de produtos para obter expressões lógicas do circuito.

![decodificador inverso](./decodificador%20inverso.gif)


 ### **Decodificador Para Display de 7 segmentos**
 
 Para o decodificador de 7 segmentos foi utilizado a tabela verdade e o mapa de karnaugh para a obtenção das expressões lógicas do circuito. Recebe um número binário e exibe o número hexadecimal no display de 7 segmentos, de 0 a F.

![decodificador](decodificador.gif)

## Conclusão
O projeto da calculadora digital foi concluído com sucesso, atendendo plenamente aos requisitos especificados. A implementação fez uso de circuitos combinacionais, como somadores, subtratores, decodificadores, multiplexadores e comparadores de magnitude, integrados de forma eficiente. A calculadora permite a realização de operações básicas entre dois números hexadecimais de um dígito, demonstrando a aplicabilidade prática dos conceitos estudados em circuitos digitais. A interface de entrada via LEDs e a exibição dos resultados em displays de 7 segmentos funcionaram de forma clara e objetiva, cumprindo todas as expectativas do projeto.



























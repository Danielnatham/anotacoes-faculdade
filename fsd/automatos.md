# Autômatos Finitos Determinísticos e Não Determinísticos

## Autômato Finito Determinístico

### Conceito

Um automato finito determinístico é feito de varias partes sendo elas o 

- um **conjuntos de estados**
- **alfabeto** que indica os simbolo de entrada permitidos 
- uma **função de transição** que indica como devera ser a mudança de estado
- um **estado inicial** que indica onde começa a leitura
- conjunto de estados que são aceitos chamado de **estados de aceitação**

### Conceito formal

um automato finito é feita pela 5-tupla de 

- Q - Conjunto finito de estados
- Σ - conjunto finito de simbolos **(alfabeto)**
- δ - **função de transição** denotada por Q x Σ -> Q
- q0 -  **estado inicial**
- F - conjunto de **estados de aceitação** onde F C(pertence) Q

 ## Operações Regulares

### Conceito

São operações realizadas no conjunto de simbolos (alfabeto), essa operações sao definidas como **operações regulares** 

Sao operações regulares:

- União A U B = { x  | x pertence A **OU** x pertence B } (a palavra deve pertencer a linguagem A ou B)
- Concatenação A o B = { xy | x pertence A  **E**  y pertence b } (a palavra deve ser aceita pela linguagem A e B)

### Operação de União

#### Prova

Primeiro a definição de um cojunto ser **fechado** a certa operação. Dizemos que um conjunto A é **fechado** para a operação X quando para cada elemento do cojunto que seja aplicada a operação X o resultado tambem estara no conjunto A.

Na questão dos AFDs, podemos dizer que o mesmo é **fechado** para a operação de união, ou seja, para toda palavra aplicada a operação de união o resultado tambem faz parte da linguagem.

TODO: Resumir a prova

## Autômatos Finitos Não Determinístico

TODO






## Fontes

- [Repositório no github](https://github.com/olegario96/INE-5415-Teoria-da-Computacao)

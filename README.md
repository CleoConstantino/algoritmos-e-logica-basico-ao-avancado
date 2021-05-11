
# Curso - Algoritmos e Lógica de Programação do básico ao avançado - 33h - Udemy - 05/2021
  
Preparação do ambiente.

## Introdução a lógica de programação
Utilizamos a lógica de programação ao todos os dias, o problema é que nós não pensamos logicamente. 
**O que é o pensamento lógico?** Se chegar em casa e estiver escuro você acende a luz, se estiver claro não precisa acender a luz. 
**Sequência lógica:** forma de encadear o pensamento para atingir determinados objetivos. Conjunto de passos para serem seguidos de forma sequencial, ou seja, não posso pular ou mudar os passos para que eu resolva o problema que eu me pus a resolver.
**Instruções lógicas:** um conjunto de regras ou normas definidas para realização de algo. As instruções lógicas são executadas de cima para baixo, ou seja o programa executa de linha a linha de cima para baixo.
**Algoritmo:** uma sequencia finita de passos que leva a execução de uma tarefa. Qualquer tarefa que siga um padrão.
**Programas:** é um algoritmo escrito em linguagem de programação compilada para o formato executável (transformar o código fonte em linguagem de máquina - código binário 1011010100).

## Desvendando algoritmos

**Pseudocódigo:** é um código escrito numa linguagem que não é código de programação, serve simplesmente para você expressar seu pensamento lógico.
**Regras para a construção de algoritmos:**  1. usar somente um verbo por frase; 2. imaginar que você está desenvolvendo um algoritmo para pessoas que não trabalham com informática;; 3. usar frases curtas e simples; 4. Ser objetivo; 5. procurar usar palavras que não tenham sentido dúbio (que causam dúvidas na pessoa que vai ler).
**Fases de um algoritmo:**  *Entrada > Processamento > Saída*. A entrada são os dados de entrada do algoritmo. O processamento são os procedimentos utilizados para chegar ao resultado final. E a saída são os dados já processados. 
Exemplo de algoritmo = problema: calcular a média final do alunos da 3ª série. Os alunos realizaram 4 provas: P1, P2, P3 e P4. Onde a média final = (P1 + P2 + P3 + P4)/4. Para criar o algoritmo fazemos 3 perguntas:

 1. Quais os dados de entrada?
 R: os dados de entrada são P1 P2 P3 P4.
 2. Qual será o processamento utilizado?
 R: Somar todos os dados de entrada e dividir por 4.
 3. Quais serão os dados de saída?
 R: Será a média final.

Exemplo de algoritmo (pseudocódigo):
Receber a nota da Prova1
Receber a nota da Prova2
Receber a nota da Prova3
Receber a nota da Prova4
Somar todas as notas
Dividir o resultado por 4
Mostrar o resultado da divisão

**Teste de mesa:** é importante fazer teste para ter certeza de que esse código está funcionando. 

## Constantes, variáveis e tipos de dados

**Constantes:** é um determinado valor fixo que não se modifica ao longo do tempo da execução de um programa.  No caso do exemplo anterior a constante é o *divisor *4**.
**Variáveis:** é um elemento da programação que possui um nome, um tipo de dados e um valor. O valor de uma variável pode variar durante a execução de um programa. Cada variável corresponde a uma posição de memória. No exemplo anterior as variáveis são: P1, P2, P3 , P4 e ás médias.
**Tipos de dados:** basicamente, podemos ter constante e variáveis de quatro tipo:

 *1. Numéricas:* utilizadas para armazenamento de números. São classificadas como *inteiras* (3, 8, 459) ou *reais* (34.5, 12.4, 11.89);
 *2. Caracteres:* utilizadas para armazenamento de caracteres literais (que não contenha números, somente texto), ex: "Juliana, "Maria", "Pedro";
 *3. Alfanuméricas:* utilizadas para armazenamento de dados que contenham letras e/ou números. Podem ser utilizadas para conter somente dados numéricos ou somente literais. Mesmo que utilizemos para armazenas dados numéricos não poderemos utilizar para operações matemática. Ex: "abacate", "olá123", "1234".
 *4. Lógicas:* utilizadas para armazenamento de dados lógicos que podem ser verdadeiro ou falso, ex: ativo = *verdadeiro*, com_fome = *falso*;

**Declaração de variáveis:** 

Numéricas:

     - inteiro: horas_trabalhadas
     - real: salario, valor_hora

Caracteres:

     - caractere: nome, empresa

Alfanumérica:

     - alfanumerico: cep

Lógicas:

     - logico: hora_extra

## Operadores

**Operadores aritméticos:**

 - Adição: +
 - Subtração: -
 - Multiplicação: *
 - Divisão: /
 - Exponenciação: **


**Hierarquia das operações aritméticas:**

 1. Parenteses: ()
 2. Exponenciação: **
 3. Multiplicação ou divisão: * ou  / (o que vier primeiro)
 4.  -- ou +: (o que vier primeiro)

**Operadores relacionais:** os operadores relacionais são utilizados para comparar valores. Estes operadores retornam valores lógicos (verdadeiro ou falso / true ou false).
|     Descrição           |Símbolo                                               |
|----------------|-------------------------------
|Igual a|`==`            
|Diferente de |`!=` |
|Maior que |`>`|
|Menor que | `<`|
|Maior ou igual a | `>=`|
|Menor ou igual a| `<=`|

**Operadores lógicos:** os operadores lógicos são utilizados para combinar resultados de expressões, retornando se o resultado final é verdadeiro ou falso / true ou false.

|     Descrição |Símbolo  |       
|---------------|--------|
|E / AND|`&&`   |         
|OU / OR |`||` |
|NÃO / NOT |`!`|

## Estruturas de decisão

**Comandos de decisão:** as principais estruturas de decisão são: "se...então" (if/then). "se...então/senão" (if...then/else) e "caso selecione" (select...case).

## Comandos de repetição

**Enquanto algo, Processar...**
O bloco de operações será executado enquanto a condição "algo" for verdadeira.

Exemplo:

    inteiro: contador = 0
    
    enquanto contador <=10, processar
    	escrever "O contador vale" + contador
    	contador = contador +1
    fim enquanto

Em programação, utilizamos o comando **while** para realizar  essa operação.

**Até que algo, Processar...**
O bloco de operações será executado até que a condição "algo" seja verdadeira.

Exemplo:

    inteiro: numero = 0
    
    até que numero = 10, processar
    	escrever "O número agora vale" + numero
    	numero = numero +1
    fim

**Processar, enquanto algo...**

Neste tipo de estrutura, primeiramente o bloco é executado, e somente depois é realizado o teste da condição. Caso a condição seja verdadeira, o bloco é executado novamente e caso seja falso o bloco é encerrado.

Exemplo:

    inteiro: numero = 1
    
    processar
    	escrever "O numero vale" + numero
    	numero = numero +1
    enquanto numero <=10
    fim
Na programação utilizamos o comando **do...while**.

**Processar, até que algo...**
Neste tipo de estrutura, primeiramente o bloco é executado, e somente depois é realizado o teste da condição. O bloco é executado até que a condição se torne verdadeira.

Exemplo:

    inteiro: numero = 1
    
    processar
    	escrever "Olá mundo"
    	numero = numero +1
    até que numero == 10
    fim

**Para**

Primeiro é verificada se a condição é verdadeira, depois é executado o bloco de comandos. Serão novamente checados e executados enquanto a condição for verdadeira.

Exemplo:

    inteiro: contador
    
    para contador = 0, enquanto contador <=10, processar
    	escrever "Olá mundo"
    	contador = contador +1
    fim

## Variáveis compostas

**Vetores:** conhecidos como *arrays unidimenssionais*, os vetores são uma estrutura de dados bastante utilizadas na programação de sistema.

Com vetores podemos guardar uma quantidade fixa de *valores do mesmo tipo*.

Declarando vetores: 
tipo: nome [tamanho]

Exemplos:
inteiro: numeros[10]
caracteres: nomes[100], frutas[10]

Os vetores são estruturas da dados indexadas, iniciando, na maioria dos casos, em 0 (zero) e indo até n-1.

Por exemplo:
inteiro: numeros[10]
O primeiro elemento será numeros[0] e o ultimo será numeros[9].

Lendo ou colocando valores nos vetores:
Inteiro: numeros[10]

numeros[0] = 34
numeros[1] =12
...
numeros[9] = 22

**Matrizes:** também conhecidos como *arrays multidimenssionais*, as matrizes, assim como os vetores são uma estrutura de dados bastante utilizadas na programação de sistemas.

Com matrizes podemos guardar uma quantidade fixa de valores do mesmo tipo com *múltiplas dimensões*.

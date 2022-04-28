# Lógica de Programação

programar= "resolver problemas"

logica= "coerência de raciocínio"

logica_de_programacao= programar + "com" + logica

Print("Lógica de programação é" + logica_de_programacao + ".")

Lógica de programação é resolver problemas com coerência de raciocínio.

Isso significa contextualizar a nossa lógica (humana) na programação de computadores, pois eles não entendem as coisas do mesmo jeito que nós. E fazemos isso buscando a melhor sequência de ações para solucionar um problema. Uma sequência de passos para resolver o problema é chamada de **algoritmo**.

## Abstração
Uma habilidade que o dev precisa desenvolver para ser um bom programador é a abstração, ou seja, a habilidade de extrair apenas o essencial para o entendimento e resolução do problema.

É importante citar esse assunto porque os problemas que precisaremos resolver normalmente não vão chegar de forma resumida. Os problemas são contados cheios de contexto, então precisamos abstrair apenas os pontos chaves para criar o nosso algoritmo.

### Variáveis 
São elementos que atribuimos valor no nosso algoritmo, e esses valores podem mudar durante o decorrer do código.

ex:

fruta= "uva"

O valor "uva" foi atribuido para a variável fruta.

ex2:

fruta: "banana"

vitamina: "de" + fruta

Também podemos atribuir uma variável ao valor de outra variável.

### Tipos de variáveis
- inteiro: número inteiro, positivo ou negativo.
- float: número decimal
- double: variavel numérica do tipo de precisão dupla
- char: apresenta caractere do tipo texto.
- string: representa um conjunto de caracteres do tipo texto
- boolean: booleana, que pode representar verdadeiro ou falso.

#### Constantes: "variáveis" que não podem ter seu valor alterado durante o código.

### Concatenação
Operação para unir o conteúdo de duas strings. strings é uma sequência de caracteres.

ex:

nome= Bruno

sobrenome= Bandeira

Concatenação seria juntar os dois 

Nome + Sobrenome

Bruno Bandeira

Não precisa ser feita só com texto. Pode ser feita com nomes e números.

### Linguagem compilada x interpretada
COMPILADA - é aquela que você escreve e depois ela é executada pelo SO (Sistema Operacional). São transforamadas em arquivo executado. 

Interpretada - o codigo fonte é interpretado por um programa pra depois ser executado. Quando vc abre um site, o codigo é interpretado pelo navegador e dps executado pelo SO.

### Desvios condicionais (SE/SENAO)
No algoritmo, podemos acrescentar condições para o caminho que o programa deve seguir. Para isso, usamor o SE e o SENAO (linguagem do Portugol)
SE tal condição for atendida, faça 1. SENAO, faça 2. Também aprendemos a usar a cadeia **escolha**

ex:

inteiro valor = 0

escolha (valor)

{

caso 1: (tal coisa)

caso 2: (tal coisa)

caso 3: (tal coisa )

caso contrario: (tal coisa)

}

### Laços de repetição
Fazer uma mesma tarefa até que um limite seja atingido. É o comando **enquanto** no Portugol

### Matriz
Conjunto de variaveis do mesmo tipo (caracteres, inteiro, real) acessíveis com um único nome. A individualização de cada variável é feita por através de índices (você indica a posição da variavel na matriz). Vetores são matrizes de uma só dimensão

ex:

cadeia Vetor[5]; //declaraum vetor de 5 posições

cadeia Matriz[5][3]; //declara uma matriz de 5 linhas e 3 colunas

cadeia frutas[4];

frutas[0]=”maça”

frutas[1]=”pera”

frutas[2]=”melão”

frutas[3]=”uva”

escreva(frutas[2])

matriz ex:

cadeia cesta[][]={{”pera”,”50”},{”feijao”,”60”},{”trigo”,”78”}}

Quando vc faz a matriz sem dizer o indice dos itens, o programa preenche automaticamente. O primeiro indice é linha, o segundo é coluna]. Em tabela, ficaria:

pera   |  50

feijao |   60

trigo  |   78

Pense que cada chave na matriz é uma linha, e que a linha pode ter vario itens espalhados pelas colunas, sendo separados por virgulas.

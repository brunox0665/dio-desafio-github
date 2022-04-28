programar= "resolver problemas"
logica= "coerência de raciocínio"
logica_de_programacao= programar + "com" + logica
Print("Lógica de programação é" + logica_de_programacao + ".")
Lógica de programação é resolver problemas com coerência de raciocínio.

Isso significa contextualizar a nossa lógica (humana) na programação de computadores, pois eles não entendem as coisas do mesmo jeito que nós. E nós fazemos isso buscando a melhor sequência de ações para solucionar um problema.
Uma sequência de passos para resolver o problema é chamada de algoritmo.

//Uma habilidade que o dev precisa desenvolver para ser um bom(a) garoto(a) de programa ( ͡° ͜ʖ ͡°) é a abstração, ou seja, a habilidade de extrair apenas o essencial para o entendimento e resolução do problema.
É importante mencionar isso aqui porque os problemas que vamos resolver na nossa carreira podem ser comparados com as questões do enem. São problemas que vem para nós cheias de contexto e que precisamos abstrair apenas os pontos chaves para criar o nosso algoritmo.

Variáveis - São elementos que atribuimos valor no nosso algoritmo, e esses valores podem mudar durante o decorrer do código.
ex:
fruta= "uva"
//eu atribui o valor "uva" para a variável fruta.
ex2:
fruta: "banana"
vitamina: "de" + fruta
//também podemos atribuir uma variável ao valor de outra variável.
tipos de variáveis -
- inteiro: número inteiro, positivo ou negativo.
float: de número decimal
double: variavel numérica do tipo de precisão dupla
char: apresenta caractere do tipo texto.
string: representa um conjunto de caracteres do tipo texto
boolean:booleana, que pode representar verdadeiro ou falso.

Constantes: "variáveis" que não podem ter seu valor alterado durante o código.

Concatenação
Operação para unir o conteúdo de duas strings.
strings é uma sequência de caracteres.

ex:
nome= Bruno
sobrenome= Bandeira
Concatenação seria juntar os dois 
ex:
Nome + Sobrenome
Bruno Bandeira
Não precisa ser feita só com texto. Pode ser feita com nomes e números.

Linguagem compilada x interpretada
COMPILADA - é aquela que você escreve e dps ela é executada pelo SO. São transforamadas em arquivo executado. 

Interpretada - o codigo fonte é interpretado por um programa pra depois ser executado. Quando vc abre um site, o codigo é interpretado pelo navegador e dps executado pelo SO.

Desvios condicionais
No algoritmo, podemos acrescentar condições para o caminho que o programa deve seguir. Para isso, usamor o SE e o SENAO (linguagem do Portugol)
SE tal condição for atendida, faça 1. SENAO, faça 2.
também aprendi a usar a cadeia * escolha *
ex:
inteiro valor = 0
escolha (valor)
{
caso 1: (tal coisa)
caso 2: (tal coisa)
caso 3: (tal coisa )
caso contrario: (tal coisa)
}

Laços de repetição - Fazer uma mesma tarefa até que um limite seja atingido.
É o comando *enquanto* no Portugol

matriz
Conjunto de variaveis do mesmo tipo (caracteres, inteiro, real) acessíveis com um único nome. A individualização de cada variável é feita por através de índices (você indica a posição da variavel na matriz)
Vetores são matrizes de uma só dimensão
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
//quando vc faz a matriz sem dizer o indice dos itens, o programa preenche automaticamente.
//o primeiro indice é linha, o segundo coluna]
em tabela, ficaria:
pera   |  50  
feijao |   60
trigo  |   78
// pense que cada chave na matriz é uma linha, e que a linha pode ter vario itens espalhados pelas colunas, sendo separados por virgulas.
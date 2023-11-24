# lambda1-java
O método sort da interface List para ordenar a lista de produtos em ordem ascendente, reorganizando os elementos que estejam em ordem crescente.  Utilizei a interface Comparator no meu Produto utilizando cinco formas para definir o Comparator no método sort.

## Comparator como objeto de uma classe separada 
Implementei a interface Comparator na classe MyComparator, do tipo Product.



## Comparator como objeto de uma classe anônima 
Desconsiderando a classe MyComparator, declarei um Comparator no programa principal, utilizando uma sintaxe de classe anônima. Não é mais necessário ter uma classe separada para implementar a interface e chamá-la posteriormente. a classe anônima ficou muito verbosa, desajeitada.



## Comparator como objeto de uma expressão lambda com chaves 
Reduzi o código utilizando expressões lambda, que são funções anônimas com a sintaxe Arrow Function, para definir a função de forma mais simplificada e concisa.



## Comparator como objeto de uma expressão lambda sem chaves 
Como essa implementação de função possui apenas uma linha, dispensei o uso das chaves e da palavra "return".



## Comparator como expressão lambda diretamente no argumento 
Em vez de declarar o Comparator separadamente e chamá-lo posteriormente no sort, coloquei a expressão lambda diretamente como argumento do sort de forma concisa e bem resumida. 

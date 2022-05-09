## List

"List" é um interface do java que permite a criação de uma lista, para manipular valores nela.

```java 
  List<Integer> numbers;
```
No entanto para instanciar uma "List" é preciso utilizar uma das classes que a implementam, como: ```ArrayList<>()``` ou ```LinkedList<>()```. por exemplo abaixo:

```java 
  numbers = new ArrayList<>();
  
  numbers = new LinkedList<>();
```
A "ArrayList" é uma lista de tamanho infinito que possui facil armazenamento e verificação de dados. No entando na "LinkedList" é mais facil excluir um valor do que na Array, ja que ao exclui-lo não ficara nenhum espaço vazio no meio da lista.

Alguns dos principais métodos das listas são:

```.add()``` -> Utilizado para adicionar valores na lista, podendo também adicionar o indice da onde sera adicionado o valor (.add(10,"Gabriel")).

```.sort()``` -> Ordena a lista de forma alfabética ou crescente.

```.clear()``` -> Limpa a lista.

```.contains()``` -> Verifica se a lista possui o valor passado como parâmetro.

```.get()``` -> Retorna o valor que está no índice passado como parâmetro.

Para iterar sobre uma lista podemos utilizar o "foreach", como no exemplo abaixo:

```java 
  for(Integer number : numbers){
    System.out.print(number);
  }
```

## Set

"Set" é uma interface parecida com a "List" porém **NÃO ARMAZENA VALOR REPETIDOS**.

```java
  Set<Integer> numbers;
  
  numbers = new TreeSet<>();
```
O exemplo acima mostra como se implementa uma variável do tipo Set, utilizando a classe "TreeSet" assim como a List o Set é uma interface, não podendo então instanciar um objeto, o que gera a necessidade de utilizar o "TreeSet", "HashSet" ou "LinkedHashSet".

"TreeSet" -> 
"HashSet" ->
"LinkedHashSet" ->
  
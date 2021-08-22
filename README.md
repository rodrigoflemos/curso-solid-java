# curso-solid-java

SOLID

Single responsability principle
Open closed principle
Liskov substitutions principle
Interface segregation principle
Dependency Inversion principle


**S: Principio da responsabilidade única**

Uma classe deveria ter apenas um único motivo para mudar

**O: Principio do aberto fechado**

Não é necessario fazer uma cirurgia de peito aberto para colocar um casaco
Entidades de software ( classes, módulos, funções, etc) devem estar abertas para extensao, porem fechadas para modificação

**L: Principio da substituiçao de Liskov**

Se q(x) ' – , a função q(x) – ' é uma propriedade demonstrável dos objetos x do tipo T, então q(y) ' - que é um outro objeto – ' deve ser verdadeiro para objetos Y do tipo S, se S for um subtipo de T
Ou seja, ao herdar de uma classe, sempre verificar se todos os atributos e metodos da classe herdada fazem sentido para a classe filha. Caso nao faça, ao chamar uma função que use a classe filha ao inves da classe mae, pode haver efeito colateral

**I: Principio da segregação de interface**
Uma classe não deveria ser forçada a depender de métodos que não utilizará

**D: Principio da inversao de dependencia**
Abstrações não devem depender de implementações. Implementações devem depender de abstrações

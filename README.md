Padroes de Projeto

1) Criacionais -> Os padrões criacionais fornecem vários mecanismos de criação de objetos, que aumentam a flexibilidade e reutilização de código já existente.
2) Estruturais -> Os padrões estruturais explicam como montar objetos e classes em estruturas maiores mas ainda mantendo essas estruturas flexíveis e eficientes.
3) Comportamentais -> Padrões comportamentais são voltados aos algoritmos e a designação de responsabilidades entre objetos.

* Comportamentais

4.Mediator

O que é:
O Mediator é um padrão de projeto comportamental que reduz o acoplamento entre os componentes de um programa, fazendo-os se comunicar indiretamente, por meio de um objeto mediador especial.

Aplicabilidade:
Utilize o padrão Mediator quando é difícil mudar algumas das classes porque elas estão firmemente acopladas a várias outras classes.
Utilize o padrão quando você não pode reutilizar um componente em um programa diferente porque ele é muito dependente de outros componentes.
Utilize o Mediator quando você se encontrar criando um monte de subclasses para componentes apenas para reutilizar algum comportamento básico em vários contextos.

Exempos de utilizacao:
java.util.Timer
java.util.concurrent.Executor#execute()
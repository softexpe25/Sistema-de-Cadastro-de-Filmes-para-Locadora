A classe Filme define os atributos (ator, genero e estoque) e o método (verificarEstoque()) que são comuns a todos os filmes no seu sistema.
todas as outras classes de filmes como: O conde de monte cristo, Armagedon e Os Mercenários (Subclasses), são "filhas" da classe filme e 
Cada uma herda a estrutura e o comportamento da classe filme. Isso significa que, por exemplo, a classe (O conde de monte cristo) já sabe que tem um atributo gênero
e um método verificarEstoque(), mesmo sem ter que declará-los explicitamente, pois herdam e devem seguir a superclasse.
As subclasses também podem adicionar seus próprios atributos e métodos, que são específicos para elas. Por exemplo, a subclasse "os mercenários" 
tem um atributo ano de lançaman e um método exibirSinopse() que são particulares dela.

Não precisamos escrever novamente nas subclasses os atributos e métodos que já estão presentes na superclasse.
Essa dinâmica de herança permite a reutilização de código e a criação de uma estrutura hierárquica e organizada.

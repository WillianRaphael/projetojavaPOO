# projetojavaPOO
1-O que é programação orientada a objetos?
R: A programação orientada a objetos é um paradigma de programação que se baseia na criação de objetos que possuem atributos e métodos específicos, permitindo a criação de programas mais modulares e escaláveis.

2-Quais são os pilares da programação orientada a objetos?
R: Os pilares da programação orientada a objetos são encapsulamento, herança, polimorfismo e abstração. Eles permitem a criação de programas mais modulares, reutilizáveis e escaláveis, tornando a manutenção e evolução do código mais fácil.

3-O que é uma classe em Java?
R:Uma classe em Java é um modelo que define as propriedades e comportamentos de objetos de um determinado tipo. Ela contém variáveis de instância, métodos, construtores e pode ser usada para criar múltiplos objetos com as mesmas características.

4-Como criar um objeto a partir de uma classe em Java?
R:Para criar um objeto a partir de uma classe em Java, é necessário utilizar a palavra-chave "new" seguida do nome da classe e dos parênteses, que podem conter argumentos para o construtor da classe. Por exemplo: "MinhaClasse objeto = new MinhaClasse();" cria um objeto da classe "MinhaClasse".

5-O que faz a palavra new no Java?
R:A palavra "new" é utilizada em Java para criar uma nova instância de uma classe, ou seja, para criar um novo objeto. Ela aloca a memória necessária para o objeto e chama o construtor da classe para inicializar suas propriedades.

6-Quais as semelhanças entre Java e C?
R:Java e C são linguagens de programação que possuem algumas semelhanças, como a sintaxe de algumas estruturas de controle de fluxo, como if-else, for, while e switch, além da possibilidade de criar funções e trabalhar com ponteiros. No entanto, Java é uma linguagem orientada a objetos, enquanto C é uma linguagem procedural.

7-Quais as diferenças entre Java e C?
R:Java é uma linguagem orientada a objetos, enquanto C é uma linguagem procedural. Java é executado em uma máquina virtual (JVM) e possui gerenciamento automático de memória, enquanto C é compilado diretamente para código de máquina e requer que o programador gerencie manualmente a alocação e desalocação de memória.

8-O que é a classe InputReader e qual é a sua função no programa?
R:InputReader é uma classe Java que permite ler entradas do usuário a partir da linha de comando ou de um arquivo de texto. Ela é usada para capturar e processar dados de entrada em programas Java.

9-Qual é a finalidade do método readDouble na classe InputReader?
R:O método readDouble na classe InputReader é usado para ler um número de ponto flutuante (double) a partir da entrada do usuário, seja da linha de comando ou de um arquivo de texto. Ele retorna o valor lido como um double para ser usado no programa.

10-O que é a interface PaymentType e como ela é utilizada no programa?
R:A interface PaymentType é um conjunto de métodos que definem os tipos de pagamento aceitos em um sistema de vendas. Ela é usada para fornecer uma abstração para os diferentes tipos de pagamento e permitir que diferentes implementações sejam usadas de forma transparente pelo restante do sistema.

11-Como a classe PaymentTypeSelector é responsável por selecionar o tipo de pagamento a ser utilizado?
R:A classe PaymentTypeSelector é responsável por criar uma instância do tipo de pagamento selecionado pelo usuário, usando a interface PaymentType para abstrair a implementação do pagamento específico. Ela utiliza uma estrutura condicional para identificar qual implementação de PaymentType deve ser utilizada e então criar uma instância dela.

12-Qual é a relação entre a classe PaymentTypeSelector e as classes PixPayment, CreditPayment e BoletoPayment?
R:A classe PaymentTypeSelector utiliza as classes PixPayment, CreditPayment e BoletoPayment para criar instâncias do tipo de pagamento selecionado pelo usuário. Essas classes implementam a interface PaymentType e definem o comportamento específico de cada tipo de pagamento.

13-O que é polimorfismo e como ele é utilizado no programa?
R:Polimorfismo é a capacidade de objetos de diferentes classes serem tratados como objetos da mesma classe. No programa, isso é possível através do uso da interface PaymentType, que permite que diferentes implementações de pagamento sejam usadas de forma transparente pelo restante do sistema.

14-Qual é a finalidade do método getName na interface PaymentType e nas classes que a implementam?
R:O método getName na interface PaymentType e nas classes que a implementam retorna o nome do tipo de pagamento. Ele é usado para exibir informações sobre o tipo de pagamento selecionado pelo usuário no momento da compra, por exemplo, em um recibo ou comprovante de pagamento.

15-O que é a classe Scanner e como ela é utilizada no programa?
R:A classe Scanner é uma classe Java que permite ler entradas do usuário a partir da linha de comando. No programa, ela é usada na classe Main para capturar a entrada do usuário e permitir que ele selecione o tipo de pagamento desejado.

16-O que é uma exceção e como ela é tratada no método selectPaymentType da classe PaymentTypeSelector?
R:Uma exceção é um evento que ocorre durante a execução de um programa e que interrompe o fluxo normal de execução. No método selectPaymentType da classe PaymentTypeSelector, exceções são tratadas usando um bloco try-catch que captura e trata qualquer exceção que possa ser lançada durante a seleção do tipo de pagamento. Se uma exceção ocorrer, uma mensagem de erro é exibida ao usuário.

17-Como seria possível adicionar um novo tipo de pagamento ao programa?
R:Para adicionar um novo tipo de pagamento ao programa, seria necessário criar uma nova classe que implemente a interface PaymentType, definindo o comportamento específico do novo tipo de pagamento. Em seguida, a classe PaymentTypeSelector seria atualizada para incluir uma nova opção de seleção para o novo tipo de pagamento e criar uma instância da nova classe durante o processamento do pagamento.

18-Qual é a importância de utilizar interfaces no desenvolvimento de sistemas orientados a objetos?
R:Interfaces permitem a criação de abstrações no código, possibilitando a separação do comportamento da implementação. Isso permite que diferentes implementações possam ser usadas de forma transparente pelo restante do sistema e permite uma maior flexibilidade e extensibilidade no desenvolvimento de sistemas orientados a objetos.

19-Qual é a diferença entre uma classe abstrata e uma interface?
R:Uma classe abstrata pode ter implementações de métodos e variáveis de instância, enquanto uma interface não pode ter implementações de métodos e pode ter apenas variáveis de interface. Uma classe pode implementar várias interfaces, mas só pode estender uma classe abstrata.

20-O Que é encapsulamento e como ele é aplicado no programa?
R:Encapsulamento é o conceito de ocultar a implementação interna de uma classe, fornecendo apenas uma interface pública para que outras classes possam interagir com ela. No programa, o encapsulamento é aplicado definindo os atributos da classe como privados e fornecendo métodos públicos para acessá-los e modificá-los, como o método getAmount() da classe Payment.

21-Como seria possível melhorar a legibilidade do programa?
R:Algumas formas de melhorar a legibilidade do programa são: usar nomes descritivos para classes, métodos e variáveis, utilizar indentação adequada, separar o código em blocos lógicos e adicionar comentários que expliquem o que cada parte do código faz.

22-Qual é a finalidade da classe Main no programa?
R:A classe Main é responsável por iniciar a execução do programa, criando um objeto PaymentTypeSelector e chamando o método selectPaymentType().

23-O que é um construtor padrão e quando ele é utilizado?
R:Um construtor padrão é um construtor que não recebe argumentos e tem uma implementação padrão (geralmente vazia). Ele é utilizado para inicializar os objetos quando nenhum argumento é passado para o construtor.

24-Como é possível proteger o programa contra erros de entrada do usuário?
R:Uma forma de proteger o programa contra erros de entrada do usuário é validar as entradas de dados antes de processá-las. Isso pode ser feito utilizando estruturas de controle, como if e try-catch, para verificar se a entrada está no formato correto ou se está dentro dos limites aceitáveis.

25-Quall é a importância de utilizar nomes descritivos para as classes, métodos e variáveis?
R:Utilizar nomes descritivos para as classes, métodos e variáveis torna o código mais legível e compreensível, facilitando a manutenção e o entendimento do funcionamento do programa.

26-O que é herança e como ela pode ser aplicada no programa?
R:Herança é um conceito de programação orientada a objetos em que uma classe pode herdar atributos e métodos de outra classe. Isso permite que as classes sejam organizadas em hierarquias e compartilhem comportamentos e características comuns. No programa, a classe PaymentTypeSelector

27-Como é possível utilizar a sobrecarga de métodos no programa?
R:A sobrecarga de métodos é utilizada no programa por meio da criação de vários métodos com o mesmo nome, porém com diferentes parâmetros de entrada. No caso específico do programa, a classe PaymentTypeSelector possui vários métodos selectPaymentType com diferentes assinaturas, sendo possível selecionar o tipo de pagamento com diferentes tipos de entrada, como um objeto PaymentType, uma string contendo o nome do tipo de pagamento ou um inteiro representando o código do tipo de pagamento. Essa técnica é útil para simplificar a utilização dos métodos, tornando mais fácil para o usuário final compreender e utilizar o sistema.

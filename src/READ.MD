1.	O que é programação orientada a objetos?
A programação orientada a objetos (POO) é um paradigma de programação que se baseia na utilização de objetos para representar entidades do mundo real ou conceitual. Esses objetos são criados a partir de classes, que definem as características e comportamentos que eles podem ter. Em POO, o foco está nas interações entre os objetos, permitindo a criação de programas mais modulares, flexíveis e fáceis de manter.
A POO é uma abordagem muito utilizada na programação moderna, presente em diversas linguagens de programação como Java, Python, C++ e Ruby. Ela permite a criação de programas mais estruturados e escaláveis, facilitando a reutilização de código e a manutenção do sistema ao longo do tempo. Com a POO, é possível desenvolver aplicações mais complexas e sofisticadas, incluindo sistemas de grande porte, jogos, aplicativos móveis, entre outros.


2. Quais são os pilares da programação orientada a objetos?
Os pilares da Programação Orientada a Objetos (POO) são encapsulamento, herança e polimorfismo.
O encapsulamento é o processo de ocultar os detalhes internos de um objeto e permitir apenas a interação por meio de uma interface pública.
Isso promove a segurança e evita que outros objetos acessem ou modifiquem dados e comportamentos que não deveriam.A herança permite que uma classe "filha" herde os atributos e métodos de uma classe "pai", e também possa adicionar seus próprios atributos e métodos exclusivos.
Isso promove a reutilização de código e ajuda a evitar a repetição desnecessária de código. O polimorfismo é a capacidade de um objeto ser tratado como um objeto de um tipo diferente, permitindo que os desenvolvedores escrevam código genérico que pode funcionar com vários tipos de objetos.
Esses três pilares são fundamentais para a POO e são amplamente utilizados em linguagens de programação orientadas a objetos.



3.	O que é uma classe em Java?
Em Java, uma classe é uma estrutura fundamental da programação orientada a objetos que define um tipo de objeto.
Ela é a base para a criação de objetos, que são instâncias dessa classe. As classes encapsulam dados (atributos) e comportamentos (métodos) relacionados a um conceito específico em um único lugar, o que torna o código mais organizado, legível e fácil de entender.
As classes em Java são definidas usando a palavra-chave "class" seguida pelo nome da classe e um bloco de código que contém os atributos e métodos da classe.
As classes também podem ser usadas como base para a herança, permitindo que outras classes derivem delas e herdem seus atributos e métodos. A classe é uma das principais estruturas de programação em Java e é fundamental para o desenvolvimento de programas orientados a objetos em uma ampla variedade de áreas, desde aplicativos de desktop até sistemas web complexos.



4.	Como criar um objeto a partir de uma classe em Java?
Em Java, um objeto é criado a partir de uma classe usando a palavra-chave "new". Para criar um objeto, primeiro você precisa ter uma classe definida com seus atributos e métodos. Depois, você pode criar uma instância dessa classe atribuindo-a a uma variável do tipo da classe e usando o operador "new" seguido do nome da classe e dos parênteses vazios.Por exemplo, suponha que temos uma classe chamada "Pessoa" com atributos como "nome" e "idade" e métodos como "andar" e "falar". Podemos criar um objeto dessa classe usando o seguinte código: "Pessoa pessoa1 = new Pessoa();"
Nesse código, estamos criando um objeto do tipo "Pessoa" e atribuindo-o à variável "pessoa1". O operador "new" é usado para alocar memória para o objeto e o construtor padrão da classe é chamado para inicializar seus atributos. Agora podemos acessar os atributos e métodos do objeto usando a notação de ponto, por exemplo: pessoa1.nome = "João";
pessoa1.idade = 30;
pessoa1.andar();
pessoa1.falar();
Dessa forma, estamos definindo o nome e a idade da pessoa e chamando seus métodos "andar" e "falar".



5.	O que faz a palavra new no Java?
Em Java, a palavra-chave "new" é usada para criar uma nova instância de uma classe.
Quando o operador "new" é usado com o nome de uma classe, ele aloca espaço na memória para um novo objeto e inicializa seus atributos com os valores padrão.
Ele também chama o construtor da classe para executar qualquer inicialização adicional que possa ser necessária. Por exemplo, suponha que temos uma classe chamada "Carro" e queremos criar um novo objeto dessa classe. Podemos usar o seguinte código: "Carro meuCarro = new Carro();"Nesse código, estamos criando um novo objeto do tipo "Carro" usando o operador "new" e atribuindo-o à variável "meuCarro". Isso aloca memória para um novo objeto "Carro" e chama o construtor padrão da classe para inicializar seus atributos. A partir daí, podemos usar a variável "meuCarro" para acessar e modificar os atributos do objeto, bem como chamar seus métodos.


6.	Quais as semelhanças entre Java e C?
Java e C são duas linguagens de programação que têm algumas semelhanças em sua sintaxe e estrutura. Ambas usam uma sintaxe semelhante para a declaração de variáveis, operadores aritméticos e estruturas de controle de fluxo, como if-else, for e while.Outra semelhança entre Java e C é que ambas são linguagens compiladas, o que significa que o código fonte é compilado para código de máquina executável antes de ser executado. Além disso, ambas suportam a alocação dinâmica de memória e a manipulação direta de ponteiros, o que é uma característica poderosa, mas também pode ser propensa a erros se não for usada com cuidado. No entanto, também há diferenças significativas entre Java e C, como a maneira como lidam com a alocação de memória, gerenciamento de exceções e a presença de um sistema de coleta de lixo em Java que gerencia automaticamente a memória.


7.	Quais as diferenças entre Java e C?
Java e C são duas linguagens de programação com diferenças significativas em sua sintaxe, estrutura e funcionalidades. Uma das principais diferenças entre elas é que C é uma linguagem de programação de baixo nível, enquanto Java é uma linguagem de programação de alto nível. Isso significa que em C, é possível acessar a memória diretamente usando ponteiros, o que pode ser poderoso, mas também pode levar a erros de segurança e vazamentos de memória.
Já em Java, o gerenciamento de memória é feito automaticamente pelo coletor de lixo, o que simplifica muito a programação.Outra diferença significativa é que Java é uma linguagem orientada a objetos, enquanto C não é.
Isso significa que em Java, todos os dados são encapsulados em objetos, que são instâncias de classes, e o código é organizado em torno de objetos e suas interações.
Já em C, é possível escrever programas estruturados que não usam objetos ou classes. Além disso, Java tem um rico conjunto de bibliotecas padrão para lidar com tarefas comuns, como entrada e saída de dados, rede e gráficos, enquanto em C essas tarefas podem ser mais complexas de serem realizadas. 


8.	O que é a classe InputReader e qual é a sua função no programa?
A classe InputReader é uma classe Java que é usada para ler dados de entrada do usuário ou de um arquivo. Ela é frequentemente usada em programas Java que exigem entrada de dados do usuário, como jogos ou aplicativos de linha de comando. A classe InputReader é uma implementação personalizada da classe Scanner Java, que oferece métodos para ler entradas de vários tipos de dados, como inteiros, doubles e strings.A função da classe InputReader em um programa Java é simplificar a leitura de dados de entrada e fornecer uma interface amigável para o usuário.
Ela encapsula a complexidade de ler dados do usuário ou de um arquivo em uma classe fácil de usar.
Além disso, a classe InputReader pode ser personalizada para fornecer mensagens de erro ou prompts personalizados para o usuário, o que ajuda a tornar o programa mais amigável e intuitivo. Em resumo, a classe InputReader é uma ferramenta útil para tornar a entrada de dados em programas Java mais fácil e eficiente.

9.	Qual é a finalidade do método readDouble na classe InputReader?
O método readDouble na classe InputReader é usado para ler um valor do tipo double a partir da entrada do usuário ou de um arquivo. Ele é usado em programas Java para obter entrada de dados do usuário ou de um arquivo em formato de número decimal de ponto flutuante.
A finalidade do método readDouble é permitir que o programa leia valores de entrada do usuário com precisão e facilidade. Ele lê os dados de entrada como uma string e tenta convertê-los em um valor double. Se a entrada do usuário não for um número double válido, o método lançará uma exceção, o que permite que o programa trate o erro e informe o usuário que sua entrada não é válida.
Em resumo, o método readDouble é uma ferramenta útil para tornar a entrada de dados em programas Java mais fácil e eficiente, permitindo que o programa leia valores de entrada do usuário com precisão e facilidade.


10.	O que é a interface PaymentType e como ela é utilizada no programa?
A interface PaymentType é uma interface Java que define um conjunto de métodos que devem ser implementados por qualquer classe que deseje representar um tipo de pagamento.
Ela define os métodos necessários para calcular o valor do pagamento, exibir informações de pagamento e atualizar informações de pagamento.No programa em questão, a interface PaymentType é utilizada para criar diferentes tipos de pagamentos, como pagamento em dinheiro e pagamento com cartão de crédito. Cada classe que implementa a interface PaymentType define os métodos necessários para representar o tipo de pagamento específico.
Isso permite que o programa trate cada tipo de pagamento de maneira uniforme e fácil de usar, sem se preocupar com os detalhes de implementação específicos de cada classe de pagamento. Em resumo, a interface PaymentType é uma ferramenta útil para definir um conjunto comum de funcionalidades para diferentes tipos de pagamento e permitir que o programa trate cada tipo de pagamento de maneira uniforme e fácil de usar.



11.	Como a classe PaymentTypeSelector é responsável por selecionar o tipo de pagamento a ser utilizado?
A classe PaymentTypeSelector é responsável por selecionar o tipo de pagamento a ser utilizado com base na entrada do usuário.
Ela utiliza a classe InputReader para ler a entrada do usuário e, em seguida, verifica a opção selecionada pelo usuário e retorna a classe de pagamento correspondente. Para realizar essa tarefa, a classe PaymentTypeSelector contém um método selectPaymentType que recebe um objeto InputReader como parâmetro.
Este método lê a entrada do usuário utilizando o objeto InputReader e, em seguida, verifica a opção selecionada pelo usuário utilizando uma instrução switch. Com base na opção selecionada, o método retorna a classe de pagamento correspondente.
Se a opção selecionada pelo usuário não corresponder a nenhuma das opções disponíveis, o método lançará uma exceção. Em resumo, a classe PaymentTypeSelector é responsável por selecionar o tipo de pagamento correto com base na entrada do usuário e retornar a classe de pagamento correspondente.


12.	Qual é a relação entre a classe PaymentTypeSelector e as classes PixPayment, CreditPayment e BoletoPayment?
A classe PaymentTypeSelector tem uma relação de dependência com as classes PixPayment, CreditPayment e BoletoPayment. Isso significa que a classe PaymentTypeSelector depende dessas classes para selecionar o tipo de pagamento correto com base na entrada do usuário. Quando o método selectPaymentType da classe PaymentTypeSelector é chamado, ele retorna a classe de pagamento correspondente com base na opção selecionada pelo usuário.
Se o usuário selecionar a opção Pix, o método retorna a classe PixPayment. Se o usuário selecionar a opção Cartão de Crédito, o método retorna a classe CreditPayment. E se o usuário selecionar a opção Boleto, o método retorna a classe BoletoPayment.As classes PixPayment, CreditPayment e BoletoPayment, por sua vez, implementam a interface PaymentType. Essa interface define um conjunto comum de funcionalidades que devem ser implementadas por cada classe de pagamento.
Isso permite que o programa trate cada tipo de pagamento de maneira uniforme e fácil de usar, sem se preocupar com os detalhes de implementação específicos de cada classe de pagamento. Em resumo, a classe PaymentTypeSelector utiliza as classes PixPayment, CreditPayment e BoletoPayment para selecionar o tipo de pagamento correto com base na entrada do usuário e utiliza a interface PaymentType para tratar cada tipo de pagamento de maneira uniforme.



13.	O que é polimorfismo e como ele é utilizado no programa?
Polimorfismo é um conceito fundamental da programação orientada a objetos que se refere à capacidade de objetos de diferentes classes serem tratados de forma uniforme por meio de uma interface comum.
Isso significa que um objeto pode ser tratado como um objeto de uma classe base (ou interface) que ele implementa, mesmo que ele seja na verdade uma instância de uma classe derivada. O polimorfismo é útil para escrever código genérico que pode lidar com diferentes tipos de objetos sem precisar se preocupar com sua implementação específica.
No programa em questão, o polimorfismo é utilizado por meio da interface PaymentType. As classes PixPayment, CreditPayment e BoletoPayment implementam essa interface, o que significa que elas têm em comum os métodos definidos na interface.
Isso permite que o programa trate cada tipo de pagamento de maneira uniforme e fácil de usar, independentemente de sua implementação específica. Por exemplo, na classe PaymentProcessor, o método processPayment recebe um objeto PaymentType como parâmetro, que pode ser uma instância de qualquer uma das classes que implementam a interface PaymentType.
O método pode, portanto, chamar os métodos definidos na interface sem se preocupar com a implementação específica da classe de pagamento passada como parâmetro. Isso torna o código mais flexível e reutilizável, permitindo que novas classes de pagamento sejam facilmente adicionadas ao programa no futuro.


14.	Qual é a finalidade do método getName na interface PaymentType e nas classes que a implementam?
O método getName na interface PaymentType e nas classes que a implementam tem como finalidade retornar o nome do tipo de pagamento. Isso permite que o sistema saiba qual é o método de pagamento selecionado pelo usuário e possa processar a transação de forma adequada.
O nome retornado pode ser utilizado para exibir informações na tela de confirmação de pagamento e também para registrar a transação no sistema de forma precisa.
Além disso, o método getName também é útil para fins de manutenção e desenvolvimento do sistema. Por exemplo, se uma nova classe de pagamento for adicionada ao sistema, ela poderá implementar a interface PaymentType e fornecer uma implementação do método getName para que possa ser utilizada pelo sistema sem necessidade de modificação do código existente.
Isso torna o sistema mais flexível e escalável, permitindo que novas funcionalidades sejam adicionadas sem comprometer a integridade do código existente.


15.	O que é a classe Scanner e como ela é utilizada no programa?
A classe Scanner é uma classe do pacote java.util que permite a leitura de dados de entrada do usuário. Ela oferece diversos métodos para a leitura de diferentes tipos de dados, como inteiros, ponto flutuante, caracteres, entre outros.
Além disso, a classe Scanner é capaz de ler dados a partir de diferentes fontes, como o teclado, arquivos e strings.No programa, a classe Scanner é utilizada para obter informações do usuário, como o valor da compra, o método de pagamento escolhido e outras informações relevantes. Para isso, é criada uma instância da classe Scanner e utilizados os métodos correspondentes para a leitura dos dados desejados.
Após a leitura, os dados são armazenados em variáveis para que possam ser utilizados posteriormente no processamento do pagamento. Dessa forma, a classe Scanner desempenha um papel fundamental na interação entre o usuário e o sistema, permitindo a entrada de dados de forma fácil e intuitiva.



16.	O que é uma exceção e como ela é tratada no método selectPaymentType da classe PaymentTypeSelector?
Uma exceção é um evento que ocorre durante a execução de um programa e que pode interromper o fluxo normal de execução. As exceções podem ser causadas por diferentes motivos, como erros de sintaxe, problemas de lógica, entradas inválidas do usuário, entre outros.
Quando uma exceção é lançada, o programa é interrompido e a exceção é propagada até que seja tratada por um bloco de código específico. O tratamento de exceções é uma prática importante na programação, pois permite que o programa continue em execução mesmo quando ocorre um erro.No método selectPaymentType da classe PaymentTypeSelector, uma exceção pode ser lançada caso o usuário selecione uma opção de pagamento inválida.
Para tratar essa exceção, é utilizado um bloco try-catch que envolve o código que faz a leitura da opção escolhida pelo usuário.
Se uma exceção for lançada, o código dentro do bloco catch é executado, exibindo uma mensagem de erro para o usuário e solicitando que ele selecione uma opção válida. Dessa forma, o programa continua em execução sem ser interrompido pela exceção lançada. Além disso, também é utilizado um bloco finally que é executado independentemente de ter ocorrido ou não uma exceção.
Nesse bloco, é fechado o objeto da classe Scanner que foi utilizado para a leitura da opção escolhida pelo usuário. Isso garante que o objeto seja fechado corretamente, mesmo se ocorrer uma exceção no meio do processo de seleção do método de pagamento.


17.	Como seria possível adicionar um novo tipo de pagamento ao programa?
Para adicionar um novo tipo de pagamento ao programa, seria necessário seguir alguns passos. Primeiramente, seria preciso criar uma nova classe que implemente a interface PaymentType.
Essa classe deve ter implementações para os métodos definidos na interface, como getName e processPayment. O método getName deve retornar uma string com o nome do novo tipo de pagamento, enquanto o método processPayment deve implementar a lógica necessária para processar o pagamento de acordo com as especificidades do novo tipo.Após criar a nova classe de pagamento, seria necessário fazer as modificações necessárias no código do programa para incluir essa nova opção de pagamento.
Isso envolveria alterar o método selectPaymentType da classe PaymentTypeSelector para incluir a nova opção de pagamento e suas funcionalidades específicas.
Também seria necessário modificar outros trechos do código que fazem referência aos tipos de pagamento existentes, como a lista de opções exibida para o usuário e a lógica que determina qual tipo de pagamento será usado para processar uma transação específica. Com essas modificações feitas, o programa estaria pronto para suportar o novo tipo de pagamento



18.	Qual é a importância de utilizar interfaces no desenvolvimento de sistemas orientados a objetos?
A importância de utilizar interfaces no desenvolvimento de sistemas orientados a objetos está relacionada à sua capacidade de definir um contrato claro entre diferentes partes do sistema, separando a definição dos métodos que uma classe deve implementar da sua própria implementação. Isso permite que diferentes classes possam implementar a mesma interface e interagir entre si de forma mais flexível e modular, promovendo a reutilização de código e a manutenibilidade do sistema como um todo
Em resumo, a utilização de interfaces é uma prática importante na programação orientada a objetos que ajuda a promover a modularidade, a flexibilidade e a reutilização de código no desenvolvimento de sistemas complexos. A definição clara dos contratos entre as diferentes partes do sistema ajuda a simplificar o desenvolvimento e a manutenção do código, tornando-o mais fácil de entender e atualizar ao longo do tempo.




19.	Qual é a diferença entre uma classe abstrata e uma interface?
Tanto as classes abstratas quanto as interfaces são mecanismos utilizados na orientação a objetos para definir um conjunto de métodos e propriedades que devem ser implementados pelas classes filhas.
A principal diferença entre as duas é que uma classe abstrata pode ter implementações de métodos, além de métodos abstratos, enquanto uma interface só pode ter a assinatura dos métodos, sem implementações.Uma classe abstrata pode ser utilizada para definir comportamentos e propriedades comuns a um grupo de classes filhas, enquanto as interfaces são mais utilizadas para definir um conjunto de comportamentos que uma classe deve implementar.
Outra diferença é que uma classe pode herdar de apenas uma classe abstrata, mas pode implementar múltiplas interfaces. Além disso, uma classe abstrata pode ter atributos, enquanto uma interface não pode ter atributos além de constantes.
No geral, a escolha entre usar uma classe abstrata ou uma interface vai depender das necessidades específicas do projeto e do conjunto de comportamentos e propriedades que se deseja definir.




20.	O que é encapsulamento e como ele é aplicado no programa?
Encapsulamento é um dos conceitos fundamentais da programação orientada a objetos que consiste em esconder os detalhes internos de uma classe e fornecer apenas uma interface pública para acesso a esses detalhes. Isso significa que o estado interno de um objeto só pode ser acessado e modificado por meio dos métodos da classe, garantindo que ele seja mantido em um estado consistente e prevenindo acesso indevido ou alterações incorretas.
Para aplicar o encapsulamento em um programa, é preciso definir os atributos da classe como privados e criar métodos públicos (ou protegidos) que permitam acessar e modificar esses atributos de forma controlada. Isso permite que a lógica da classe seja protegida de alterações externas e evita que o estado interno do objeto seja modificado de forma incorreta ou inesperada.
Além disso, o encapsulamento também ajuda a promover a modularidade e a manutenibilidade do código, pois torna mais fácil fazer alterações em uma classe sem afetar o funcionamento de outras partes do sistema.


21.	Como seria possível melhorar a legibilidade do programa?
O código apresentado já está relativamente legível, mas algumas melhorias podem ser feitas para torná-lo ainda mais fácil de entender. Aqui estão algumas sugestões:

1- Use nomes de variáveis mais descritivos: Por exemplo, em vez de "valor", talvez fosse melhor usar "valorDaCompra" ou "valorTotal". Isso tornaria mais claro o que essa variável representa.

2- Adicione comentários explicativos: Embora o código já seja relativamente fácil de entender, pode ser útil adicionar alguns comentários explicando o que cada parte do código faz. Isso ajudaria pessoas que estão lendo o código pela primeira vez a entender a lógica por trás dele.

3- Use espaçamento consistente: Embora o código já esteja bem organizado, algumas partes do código têm mais espaçamento do que outras. Usar espaçamento consistente em todo o código ajudaria a torná-lo mais legível e fácil de seguir.




22.	Qual é a finalidade da classe Main no programa?
A classe Main é o ponto de entrada do programa. Ela contém o método main, que é o primeiro método a ser executado quando o programa é iniciado. O objetivo da classe Main é inicializar os objetos necessários e iniciar a execução do programa.
No programa em questão, a classe Main é responsável por criar o objeto PaymentTypeSelector e chamar o método selectPaymentType para iniciar o processo de seleção do tipo de pagamento.
Ela também é responsável por exibir o resultado do processamento da transação, que é o valor total da transação e o tipo de pagamento escolhido pelo usuário. Além disso, a classe Main também trata possíveis exceções que possam ocorrer durante a execução do programa, exibindo mensagens de erro para o usuário e encerrando o programa de forma adequada.




23.	O que é um construtor padrão e quando ele é utilizado?
Um construtor padrão é um método especial de uma classe que não recebe nenhum parâmetro e é utilizado para criar um objeto daquela classe.
Ele é criado automaticamente pelo compilador caso não seja definido nenhum outro construtor na classe. O construtor padrão é responsável por inicializar as variáveis de instância da classe com valores padrão ou nulos.
O construtor padrão é utilizado sempre que um objeto é criado através da instrução "new" sem passar nenhum argumento para o construtor. Ele também pode ser chamado explicitamente dentro de outro construtor da classe, caso seja necessário executar alguma inicialização adicional antes da criação do objeto.
Caso a classe possua outros construtores definidos, o construtor padrão pode ser sobrescrito por outro construtor que receba parâmetros, de forma que seja possível inicializar as variáveis de instância de acordo com os argumentos passados na criação do objeto.




24.	Como é possível proteger o programa contra erros de entrada do usuário?
Uma forma de proteger o programa contra erros de entrada do usuário é através da validação das entradas. Isso significa verificar se as entradas estão no formato e nos valores esperados pela aplicação. Por exemplo, se a aplicação espera um número inteiro, é preciso verificar se o valor informado pelo usuário é de fato um número inteiro.
Caso contrário, o programa deve informar ao usuário que a entrada é inválida e solicitar que ele insira um valor válido.Outra forma de proteger o programa é através do tratamento de exceções. O tratamento de exceções permite que o programa intercepte erros que ocorram durante a execução e possa tratá-los de forma adequada. Por exemplo, se a aplicação espera que um arquivo esteja presente em um determinado diretório e o arquivo não é encontrado, o programa pode lançar uma exceção informando ao usuário que o arquivo não foi encontrado.
O usuário então pode ser direcionado para inserir um arquivo válido ou realizar outras ações para resolver o problema. É importante que o programa informe ao usuário qual foi o erro ocorrido e o que pode ser feito para resolvê-lo. Isso torna a aplicação mais amigável e ajuda o usuário a entender melhor como utilizar a aplicação.



25.	Qual é a importância de utilizar nomes descritivos para as classes, métodos e variáveis?
A utilização de nomes descritivos para as classes, métodos e variáveis é extremamente importante na programação, uma vez que torna o código mais fácil de entender e manter. Quando o código é escrito com nomes descritivos, outras pessoas que precisam ler ou modificar o código podem entender mais facilmente o que está acontecendo em cada parte dele, sem precisar se preocupar em decifrar nomes confusos ou abreviações obscuras.
Além disso, nomes descritivos também ajudam os desenvolvedores a escrever código mais preciso e menos propenso a erros, uma vez que os nomes podem refletir exatamente o que uma classe, método ou variável faz. Isso torna mais fácil evitar erros de programação, como usar uma variável ou método de maneira incorreta, o que pode economizar tempo e esforço na depuração de problemas.


26.	O que é herança e como ela pode ser aplicada no programa?
Herança é um conceito fundamental da programação orientada a objetos que permite que uma classe filha herde atributos e métodos de uma classe pai já existente. A partir daí, a classe filha pode utilizar esses atributos e métodos em suas próprias implementações, bem como adicionar novos atributos e métodos.
A herança é aplicada por meio da declaração da classe filha, que especifica a classe pai que ela irá herdar.
A herança é uma técnica importante para a reutilização de código e a simplificação da estrutura de programas orientados a objetos. Ela permite a criação de hierarquias de classes, em que as classes mais especializadas herdam características de classes mais genéricas.
Além disso, a herança permite a criação de polimorfismo, que é a capacidade de objetos de diferentes classes responderem a uma mesma mensagem de forma diferente. Com isso, é possível criar programas mais flexíveis, modulares e fáceis de manter ao longo do tempo.



27.	Como é possível utilizar a sobrecarga de métodos no programa?
 A sobrecarga de métodos é um recurso da programação orientada a objetos que permite que uma classe tenha vários métodos com o mesmo nome, mas com diferentes parâmetros. Isso significa que métodos com nomes iguais podem ser utilizados para realizar tarefas diferentes, dependendo dos parâmetros que são passados para eles.
Para utilizar a sobrecarga de métodos em um programa, basta definir os métodos na classe com o mesmo nome, mas com diferentes listas de parâmetros. Isso permite que diferentes tipos de dados possam ser processados pelo mesmo método, desde que sejam passados na ordem correta.
A sobrecarga de métodos é útil para melhorar a legibilidade do código e torná-lo mais flexível, mas deve ser utilizada com cuidado para evitar ambiguidades e confusões na hora de determinar qual método deve ser executado.
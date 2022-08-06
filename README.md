# Atividade: Orientação a Objetos - Lista 04
## Orientações

1. Cada uma das questões deve ser entregue dentro de um pacote. Exemplo: "questao01","questao02",...,"questaoXX".

1. Dentro de cada pacote deve ter uma classe chamada Principal que deverá ter o método main.

1. Para todas as atividades, utilize a classe Principal para criar instâncias de objetos das classes criadas e realizar testes.

# Atividades

## Para todas as questões, sempre que possível aplique o encapsulamento.


1. Construa uma classe que represente computacionalmente uma caixa. Leve em consideração que a caixa tem um tamanho, um material, pode estar aberta ou fechada, cheia ou vazia. 

1. Construa uma classe que represente computacionalmente uma cafeteira. Adicione os seus atributos e comportamentos. Lembre-se que, para fazer um café é preciso adicionar água e pó de café. Após ter bebido todo o café, é preciso limpar e adicionar água novamente caso queria fazer um outro café.    

1. Em um contexto de um jogo de corrida onde o jogador pode pilotar um carro, construa uma classe que represente os carro, leve em considerações as atributos e comportamentos pertinentes ao contexto.

1. Em um contexto de um jogo RPG (Role Playing Game) onde o jogador é ambientado em um mundo virtual de duas dimensões e controla um personagem que pode atacar ou se defender de outros jgoadores ou NPCs (personagens não jogáveis). Construa uma classe que represente esses personagens, leve em conta as seguintes considerações:
    * O personagem deve um nome.
    * O personagem deve poder se mover para cima, baixo, esquerda e direita.
    * O personagem deve ter uma quantidade de vida.
    * O personagem deve ter uma uma determinada quantidade de pontos de força.
    * O personagem deve ter uma uma determinada quantidade de pontos de defesa.
    * Um personagem poderá atacar outro, e ao efetuar o ataque uma determinada quantidade de pontos de vida deferá ser descontada do personagem que sofreu o ataque. (Para saber a quantidade de pontos de vidas que deverá ser removido, utilize a quantidade de pontos de defesa do defensor e a quantidade de pontos de ataque do atacante ).
    * Caso um jogador esteja sem pontos de vida, não poderá mais receber ataques.
    * Construa uma método que imprima todos os detalhes do personagem.

1. Observe o diagrama de classes das classes Carro e Motor e implemente implemente-as. Considere as seguintes regras para definir os comportamentos:
    * Na classe motor, quando o carro for ligado ou desligado, além de alterar o valor do atributo ligado, também imprima a mensagem "O Carro foi ligado" ou "O carro foi desligado".
    * O moto também será responsável por imprimir mensagens de "Acelerando" quando este método for acionado.
    * Os métodos ligar, desligar e acelerar do carro deverão acionar os respectivos métodos no seu atributo da classe Motor.

    ![Diagrama UML Carro](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/IFNMG-Almenara-Classes/modificadores-de-acesso/main/assets/questao04/carro-uml.iuml?token=GHSAT0AAAAAABR4VPIHUME73YL7ZISKUZKEYXOXLQA)

1. Paulo é dono de uma em loja de venda de materiais para construção. Paulo precisa de um programa para gerenciar os clientes e vendas. Uma das prioridades do Paulo é manter o cadastro de clientes. Você foi contrato para construir o programa.

    * A prioridade do Paulo é o cadastro dos clientes, ficou decidido que seria a primeira parte do programa que seria desenvolvido. Crie uma classe para representar o cliente, adicione atributos e métodos necessários.
    * Continuando o desenvolvimento do programa para a loja do Paulo. Construa uma classe que represente os produtos da loja. Adicione atributos e métodos.
    * Após ter criado as classes que representam o cliente e o produto, você percebeu que precisava partir para o desenvolvimento da parte do software que efetuar a venda. Uma venda é composta pelo cliente, um grupo de produtos e suas quantidades. Construa uma ou mais classes para representar o processo de venda. 
    * Construa o diagrama de classes para as classes criadas.

1. O Instituto Federal do Norte de Minas Gerais esta prestes a lançar o banco  IFBank que vai atender a todos os alunos e funcionários do instituto. Você foi contrato para construir o programa. 

    * Crie uma classe que represente o cliente. É importante que um dos atributos da classe identifique se o cliente é aluno ou funcionário. Adicione atributos e métodos.
    * Construa uma classe que represente uma conta. A conta deve ao ter ao menos o cliente, número e o saldo. Deve ser possível depositar um valor, sacar um valor e consultar o saldo. Adicione atributos e métodos.    
    * Construa o diagrama de classes para as classes criadas.

1. Você foi contratado para participar do desenvolvimento de um software de RH (Recursos Humanos). Inicialmente você deverá construir a classe para representar os funcionários e uma classe que será responsável pelo processamento das folhas de pagamento. Observe o diagrama UML.
    * O método calcularFolhaDePagamento deverá imprimir a lista de funcionarios cadastrados da folha de pagamento em conjunto com o seu salário acrescido de R$100 para cada um de seus filhos.
    
    ![Diagrama UML Carro](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/IFNMG-Almenara-Classes/modificadores-de-acesso/main/assets/questao04/carro-uml.iuml?token=GHSAT0AAAAAABR4VPIHUME73YL7ZISKUZKEYXOXLQA)
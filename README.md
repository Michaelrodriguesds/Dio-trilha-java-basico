# Projeto ContaBanco

## Descrição
O projeto `ContaBanco` é um programa Java simples que solicita ao usuário informações sobre uma conta bancária e exibe uma mensagem de confirmação com os detalhes fornecidos. Este projeto foi desenvolvido com o objetivo de praticar a leitura de dados via terminal, manipulação de variáveis, concatenação de strings e uso da classe `Scanner`.

## Funcionalidades
- Solicitação de número da conta bancária.
- Solicitação de número da agência bancária.
- Solicitação do nome do cliente.
- Solicitação do saldo inicial da conta.
- Exibição de uma mensagem de confirmação com os detalhes da conta.

## O que Aprendi
- Como usar a classe `Scanner` para ler entradas do usuário via terminal.
- Declaração e uso de variáveis de diferentes tipos (inteiro, string, decimal).
- Manipulação e concatenação de strings em Java.
- Estrutura básica de um programa Java, incluindo a definição da classe principal e o método `main`.
- Boas práticas ao trabalhar com entradas de usuário, como consumir a nova linha residual após ler um número com `nextInt()`.

## Explicação das Funções e Variáveis

- **Classe `ContaTerminal`**: A classe principal do programa onde todas as operações são realizadas.

- **Método `main`**: O ponto de entrada do programa. Contém a lógica principal para solicitar e exibir informações da conta bancária.

- **Variáveis**:
  - `Scanner scanner`: Objeto usado para ler entradas do usuário.
  - `int numero`: Armazena o número da conta bancária fornecido pelo usuário.
  - `String agencia`: Armazena o número da agência bancária fornecida pelo usuário.
  - `String nomeCliente`: Armazena o nome do cliente fornecido pelo usuário.
  - `double saldo`: Armazena o saldo inicial da conta fornecido pelo usuário.
  - `String mensagem`: Armazena a mensagem final de confirmação com os detalhes da conta, construída a partir das entradas do usuário.

## Exemplo de Uso
Quando o programa é executado, ele solicita sequencialmente o número da conta, número da agência, nome do cliente e saldo inicial. Após inserir todas as informações, o programa exibe uma mensagem como a seguinte:


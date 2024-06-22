![](https://hermes.dio.me/tracks/648ef080-6c4b-4e54-bf72-34f62030f350.png)

README: Sistema Bancário Python
Este é um sistema bancário básico desenvolvido em Python, focado em funcionalidades essenciais para gerenciar contas e usuários. Abaixo estão descritas as principais funcionalidades e como utilizar o sistema.

Funcionalidades Implementadas
Depósito

Permite realizar depósitos em uma conta bancária especificada pelo usuário.
Saque

Permite realizar saques, com verificação de saldo disponível, limite de saques diários e limite de valor por saque.
Extrato

Exibe o extrato da conta bancária, mostrando as transações realizadas e o saldo atual.
Nova Conta

Permite a criação de uma nova conta bancária associada a um usuário já cadastrado.
Listar Contas

Lista todas as contas bancárias criadas no sistema, mostrando informações básicas de cada uma.
Novo Usuário

Permite o cadastro de um novo usuário, exigindo informações como CPF, nome completo, data de nascimento e endereço.
Sair

Encerra a execução do programa.
Como Utilizar
Para utilizar o sistema, execute o arquivo desafio_otimizando_sistema_bancario.py. Isso iniciará o programa e exibirá um menu interativo no terminal. Utilize as opções do menu digitando o caractere entre colchetes correspondente à ação desejada. A seguir, um breve resumo das opções:

[d] Depositar: Solicita o valor do depósito e adiciona ao saldo da conta selecionada.

[s] Sacar: Solicita o valor do saque e verifica se é possível realizar a operação, considerando saldo disponível e limitações de saques diários.

[e] Extrato: Exibe todas as transações realizadas na conta e o saldo atual.

[nc] Nova conta: Cria uma nova conta bancária associada a um usuário existente.

[lc] Listar contas: Mostra informações básicas de todas as contas bancárias cadastradas.

[nu] Novo usuário: Permite o cadastro de um novo usuário no sistema.

[q] Sair: Encerra a execução do programa.

Observações Importantes
O sistema utiliza um limite de saques diários (LIMITE_SAQUES = 3) e um limite de saque por operação (limite = 500), configurados no início do programa.

É possível cadastrar múltiplos usuários e associar contas a eles, desde que o CPF seja único.

Considerações Finais
Este sistema foi desenvolvido como parte de um desafio para otimização de um sistema bancário simples em Python. Caso tenha sugestões de melhorias ou identifique bugs, sinta-se à vontade para contribuir diretamente no código.

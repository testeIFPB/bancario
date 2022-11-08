Descrição do Sistema Bancário

Ao abrir uma conta o cliente informará seus dados pessoais ao funcionário do banco para ser armazenado no sistema. Quando cadastrado o cliente receberá por email suas informações da conta e receberá por correio seu cartão.

Depois de cadastrado o sistema bancário oferece ao cliente algumas opções como depósitos, saques, empréstimos e investimentos. 

Por meio do caixa eletrônico existem as opções de verificar o saldo,  sacar, depositar, ver extrato e transferência.

Ao inserir seu cartão o caixa eletrônico irá pedir a senha do cliente. Depois de fornecer sua senha, o caixa verificará se está correta. O caixa exibirá as operações possíveis.

O cliente poderá escolher em realizar um saque. Então o caixa eletrônico perguntará o valor a ser sacado. 

O cliente fornecerá o valor que deseja sacar, então o caixa eletrônico fornece a quantia desejada e emite o recibo para o cliente. O cliente retira a quantia e o recibo, caso for finalizada a operação.

Historia de usuarios

1 - Como funcionário, eu gostaria de cadastrar os dados do cliente no sistema bancário.
2 - Como funcionário, eu gostaria de gerenciar a conta do cliente.
3 - Como cliente, eu gostaria de receber notificações sobre a conta bancária por email
4 - Como cliente, eu gostaria de receber meu cartão via correio.
5 - Como cliente, eu gostaria de ver meu saldo.
6 - Como cliente, eu gostaria de realizar um saque.
7 - Como cliente, eu gostaria de realizar um depósito.
8 - Como cliente, eu gostaria de realizar um empréstimo.
9 - Como cliente, eu gostaria de realizar um investimento.
10 - Como cliente, eu gostaria de realizar uma transferência
11 - Como cliente, eu gostaria de emitir o extrato da movimentação da conta nos últimos 30 dias.

Documentação de casos uso 
 
saque

ator: cliente
fluxo normal: 
1 - cliente insere o cartão
2 - cliente coloca a senha.
3 - cliente informa o valor que deseja sacar
4 - o caixa eletrônico efetua o saque
5 - o caixa eletrônico pergunta se o cliente deseja fazer uma nova operação

extensões

2a - Se a senha estiver incorreta, verifique a senha.
3a - Se o valor estiver acima do saldo atual, solicite um novo valor.
3b - Se o valor está correto, confirme a operação.



Documentação de casos uso 
 
transferências

ator: cliente
fluxo normal: 
1 - Cliente informa os dados da conta do destinatário.
2 - Cliente informa o valor que deseja transferir.
3 - sistema efetua transferência
4 - sistema pergunta se o cliente deseja fazer uma nova operação

extensões

1a - Se os dados estiverem incorretos, solicitar um novo dado.
2a - Se o valor estiver acima do saldo atual, solicite um novo valor.
2b - Se o valor está correto, confirme a operação.

Documentação de casos uso 
 
Empréstimo

ator: Cliente 
fluxo normal:
1 - cliente insere o cartão
2 - cliente coloca a senha.
3 - cliente informa o valor que desejado para empréstimo
4 - o sistema realizará o empréstimo 
5 - o caixa eletrônico pergunta se o cliente deseja fazer uma nova operação

extensões
2a - Se a senha estiver incorreta, verifique a senha.
3a - Se o valor está correto, confirme a operação

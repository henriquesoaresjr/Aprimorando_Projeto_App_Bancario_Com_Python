# Aprimorando_Projeto_App_Bancario_Com_Python

## Sistema Bancário Simples em Python

Este projeto consiste em  aprimorar um sistema bancário básico que desenvolvi em Python anteriormente, proporcionando uma experiência interativa de gestão de conta. O sistema oferece funcionalidades essenciais, como depósito, saque, consulta de extrato, cadastro de conta e usuarios. Essa foi uma atividade realizada junto com o instrutor, realizando apenas algumas alterações na estrutura e mensagens de retorno se comparadas ao do instrutor. Este sistema bancário simples em Python é uma ferramenta educativa e prática para entender os conceitos básicos de programação e lógica de controle financeiro. Personalize e aprimore conforme necessário para atender às suas necessidades específicas

### Funcionalidades Principais:

1. **`depositar(saldo, valor, extrato)`**:
   - Permite que o usuário deposite um valor na conta.
   - Atualiza o saldo e o extrato com a transação de depósito.

2. **`sacar(saldo, valor, extrato, limite, numero_saques, limite_saques)`**:
   - Realiza saques da conta, considerando limites de saldo e número máximo de saques diários.
   - Atualiza o saldo, o extrato e o contador de saques.

3. **`exibir_extrato(saldo, extrato)`**:
   - Mostra o extrato da conta, incluindo todas as transações realizadas e o saldo atual.

4. **`criar_usuario(usuarios)`**:
   - Cria um novo usuário com informações como nome, data de nascimento e endereço.
   - Adiciona o usuário à lista de usuários existentes.

5. **`criar_conta(agencia, numero_conta, usuarios)`**:
   - Cria uma nova conta bancária associada a um usuário existente.
   - Retorna os detalhes da conta criada.

6. **`listar_contas(contas)`**:
   - Lista todas as contas existentes, exibindo agência, número da conta e titular.

7. **`main()`**:
   - Função principal que gerencia o fluxo do programa.
   - Oferece um menu interativo para o usuário escolher entre as operações disponíveis.

Essas funções formam a base do sistema bancário e permitem a interação com os usuários.

### Como Utilizar:
- **Depósito**: Selecione a opção 'Depositar' e insira o valor desejado para realizar um depósito na conta.
- **Saque**: Escolha a opção 'Sacar' para retirar fundos da conta. Lembre-se do limite diário estabelecido.
- **Extrato**: Consulte o extrato para revisar as transações recentes e o saldo atual da conta.
-  ** Cadastrar conta**: Escolha essa função para simular um cadastro de conta bancaria.
-   ** Cadastro de usuarios**: Escolha essa função para simular um cadastro de titular de conta bancaria

# Resumo: Funções para Criar Usuários e Contas Bancárias

Neste resumo, exploraremos duas funções essenciais para o sistema bancário em Python: `criar_usuario` e `criar_conta`. Essas funções permitem a criação de novos usuários e contas bancárias, respectivamente.

## 1. Função `criar_usuario`
A função `criar_usuario` é responsável por adicionar novos usuários à lista de usuários existentes. Ela segue os seguintes passos:

1. Solicita o CPF (somente números) do novo usuário.
2. Verifica se já existe um usuário cadastrado com o mesmo CPF.
3. Se não houver um usuário com o CPF informado, coleta informações adicionais:
   - Nome completo.
   - Data de nascimento (no formato dd-mm-aaaa).
   - Endereço (logradouro, número, bairro, cidade e estado).
4. Adiciona o novo usuário à lista de usuários existentes.

## 2. Função `criar_conta`
A função `criar_conta` permite a criação de contas bancárias associadas a um usuário. Veja como ela funciona:

1. Solicita o CPF do usuário para o qual a conta será criada.
2. Verifica se o usuário com o CPF informado existe.
3. Se o usuário for encontrado, cria uma nova conta com os seguintes detalhes:
   - Agência.
   - Número da conta.
   - Referência ao usuário associado.
4. Retorna os detalhes da conta criada.


## Conclusão
Esse sistema bancário simples é uma ferramenta educativa para entender conceitos básicos de programação e lógica financeira. Personalize e expanda conforme necessário para atender aos requisitos específicos do seu projeto. Ainda estou no inicio de aprendizagem no momento que realizei essa atividade, mas considero muito importante para evoluir meu conhecimento e desenvolvimento na programação em linguagem Python, e para que esses conceitos me ajudem no futuro em outras linguagens que vou estudar.

Se você tiver mais perguntas ou precisar de mais informações, fique à vontade para perguntar! 😊

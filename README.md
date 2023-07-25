# Desafio de projeto prático proposto pela Potência Tech powered by iFood | Ciência de Dados em conjunto com a DIO.

## Criando um Sistema Bancário com Python

### **OBJETIVO GERAL V.01**
<p>Criar um sitema bancário com as operações: Sacar, depositar e visualizar extrato.</p>

### **PROJETO V.01**
<p>Fomos contratados por um grande banco para desenvolver o seu novo sistema. Esse banco deseja modernizar suas operações e para isso escolheu a linguaguem Python. Para a primeira versão do sistema devemos implementar apenas 3 operações: depósito, saque e extrato.</p>

   * #### **Operação de depósito V.01**
<p>Deve ser possivel depositar valores positivos para a minha conta bancária. A v1 do projeto trabalha apenas com 1 usuário, dessa forma não precisamos nos preocupar em identificar qual é o número da agência e conta bancária. Todos os depósitos devem ser armazenados em uma variável e exibidos na operação de extrato;</p>

   * #### **Operação de saque V.01**
<p>O sistema deve permitir realizar 3 saques diários com limite máximo de R$ 500,00 por saque. Caso o usuário não tenha saldo em conta, o sistema deve exibir uma mensagem informando que não será possível sacar o dinheiro por falta de saldo. Todos os saques devem ser armazenados em uma variável e exibidos na operação de extrato;</p>

   * #### **Operação de extrato V.01**
<p>Essa operação deve listar todos os depósitos e saques realizados na conta. No fim da listagem deve ser exibido o saldo atual da conta.</p>
<p>Os valores dever ser exibidos utilizando o formato R$ XXXX.XX, exemplo: "1500.45 = R$ 1500.45".</p>

<hr>

### **OBJETIVO GERAL V.02**
<p>Separar as funções existentes de saque, depósito e extrato em funções. Criar duas novas funções: cadastrar usuário (cliente) e cadastrar conta bancária.</p>

### **PROJETO V.02**
<p>Precisamos deixar nosso código mais modularizado, para isso vamos criar funções para as operações exixtentes: sacar, depositar e visualizar histótico. Além disso, para a versão 2 do nosso sistema precisamos criar duas novas funções: criar usuário (cliente do banco) e criar conta corrente (vincular com usuário).</p>

    * #### **Separação de funções**
        <p>Devemos criar funções para todas as operações do sistema. Para exercitar tudo o que aprendemos neste módulo, cada função vai ter uma regra na passagem de argumentos. O retorno e a forma como serão chamadas, pode ser definida por você da forma que achar melhor;</p>

    * #### **Saque**
        <p>A função saque deve receber os argumentos apenas por nome (keywood only). Sugestão de argumentos: saldo, valor, extrato, limite, numero_saques, limite_saques. Sugestão de retorno: saldo e extrato;</p>

    * #### **Depósito**
        <p>A função depósito deve receber os argumentos apenas por posição (positional only). Sugestão de argumentos: saldo, valor, extrato. Sugestão de retorno: saldo e extrato</p>

    * #### **Extrato**
        <p>A função extrato deve receber os argumentos por posição e nome (positional only e keyword only). Argumentos posicionais: saldo, argumentos nomeados: estrato</p>

    * #### **Novas funções**
        <p>Precisamos criar novas funções: criar usuários e criar conta corrente. Fique a vontade para adicionar mais funções, exemplo: listar contas.</p>

    * #### **Criar usuários (cliente)**
        <p>O programa deve armazenar os usuários em um lista, um usuário é composto por: nome, data de nascimento, cpf e endereço. O endereço é uma string com o formato: logradouro, número - bairro - cidade/sigla estado. Deve ser armazenado somente os números do CPF. Não podemos cadastrat 2 usuários com o mesmo CPF.</p>

    * #### **Criar conta corrente**
        <p>O programa deve armazenar contas em uma lista, uma conta é composta por agência, número da conta e usuário. O número da conta é sequencial, iniciando em 1. O número da agência é fixo: "0001". O usuário pode ter mais de uma conta, mas uma conta pertence a somente um usuário.</p>

    * #### **Dica**
        <p>Para Vincular um usuário a uma conta, filtre a lista de usuários buscando o número do CPF informado para cada usuário da lista.</p> 



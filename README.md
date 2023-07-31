# Projeto de Sistema de Cadastro Bancário

Este é um projeto desenvolvido para a disciplina de Banco de Dados com o objetivo de criar um sistema de cadastro bancário. O sistema permite realizar operações básicas de um banco, como cadastrar contas, consultar informações, alterar dados, remover contas e exibir todas as contas cadastradas.

## Funcionalidades

- Cadastrar Conta: Permite cadastrar uma nova conta bancária informando o número da conta, o nome do cliente e o saldo inicial.

- Consultar Conta: Permite consultar os dados de uma conta informando o número da conta. Exibe informações como número da conta, nome do cliente e saldo atual.

- Alterar Conta: Permite alterar os dados de uma conta, como o nome do cliente e o saldo. É necessário informar o número da conta a ser alterada.

- Remover Conta: Permite remover uma conta cadastrada, informando o número da conta a ser removida.

- Exibir Todas as Contas: Exibe uma lista com todas as contas cadastradas no sistema, mostrando o número da conta, o nome do cliente e o saldo atual.

- Sair do Sistema: Encerra a execução do programa.

## Requisitos

- Java 8 ou superior instalado no sistema.

- MySQL instalado e configurado.

- Driver JDBC do MySQL configurado no classpath do projeto.

## Como Executar o Projeto

1. Clone o repositório para o seu computador.

2. Crie um banco de dados MySQL com o nome "banco_bancario".

3. Execute o script SQL "criar_tabela_conta.sql" para criar a tabela "conta" no banco de dados.

4. Configure as informações de conexão com o banco de dados no arquivo "Conexao.java" do projeto.

5. Compile o código Java.

6. Execute o programa.

## Contribuições

Contribuições são bem-vindas! Se você deseja contribuir com melhorias, correções de bugs ou novas funcionalidades, sinta-se à vontade para enviar um pull request.

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE). Sinta-se à vontade para usá-lo e modificá-lo de acordo com as suas necessidades.

**Nota:** Este projeto é apenas para fins acadêmicos e não deve ser utilizado para fins de produção ou para manipulação de dados sensíveis.

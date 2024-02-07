# Sistema Bancário 2ª Versão

## Contexto do projeto

Fomos novamente selecionados pelo mesmo banco, desta vez para realizar uma atualização crucial em seu sistema. O banco está empenhado em aprimorar suas operações e decidiu utilizar a linguagem Python como parte do processo de modernização. Na segunda versão do sistema, temos a responsabilidade não apenas de manter as três operações fundamentais - depósito, saque e extrato - mas também de incorporar duas novas funcionalidades: cadastrar usuário (cliente) e cadastrar conta bancária.

## Objetivo do projeto

Separar as funções existentes de saque, depósito e extrato em funções. Criar duas novas funções: cadastrar usuários (clientes) e cadastrar conta bancária. É necessário deixar o código mais modularizado, para isso vamos criar funções para as operações existentes.

## Saque 

A função saque deve receber os argumentos apenas por nomes (keyword only). Sugestão de argumentos: saldo, valor, extrato, limite, numero_saques, limite_saques. Sugestão de retorno: saldo e extrato.

## Depósito

A função depósito deve receber os argumentos apenas por posição (positional only). Sugestão de argumentos: saldo, valor, extrato. Sugestão de retorno: saldo e extrato.

## Extrato

A função extrato deve receber os argumentos por posição e nome (positional only e keyword only). Argumentos posicionais: saldo, argumentos nomeados: extrato.

## Criar Usuário

O programa deve armazenar os usuários em uma lista, um usuário é composto por: nome, data de nascimento, CPF e endereço. O endereço é uma string com o formato: logradouro, nro - bairro - cidade/sigla estado. Deve ser armazenado somente os números do CPF. Não podemos cadastrar 2 usuários com o mesmo CPF.

## Criar Conta Corrente 

O programa deve armazenar contas em uma lista, uma conta é composta por agência, número da conta e usuário. O número da conta é sequencial, iniciando em 1. O número da agência é fixo: "0001". O usuário pode ter mais de uma conta, mas uma conta pertence a somente um usuário.

## Filtrar Usuário

Verifica se o usuário existe no sistema ou não.

## Listar Contas

Printa na tela todas as contas dos usuários cadastradas.

## Tecnologias Utilizadas

- Python 3.10.9

## Contribuições 

Contribuições são bem vindas. Sinta-se a vontade para sugerir melhorias e possíveis correções no código.

## Autor 

Jadeson Bruno Albuquerque da Silva

[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jadeson-bruno-228450101/)
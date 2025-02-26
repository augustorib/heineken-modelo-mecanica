# Projeto Conceitual de Banco de Dados – Mecânica

Este projeto faz parte da criação de um modelo conceitual de uma oficina mecânica.

## Requisitos

- Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica.
- Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões periódicas.
- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma Ordem de Serviço (OS) com data de entrega.
- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra.
- O valor de cada peça também irá compor a OS.
- O cliente autoriza a execução dos serviços.
- A mesma equipe avalia e executa os serviços.
- Os mecânicos possuem código, nome, endereço e especialidade.
- Cada OS possui: número, data de emissão, valor, status e uma data para conclusão dos trabalhos.

## Objetivo

Criar o esquema conceitual para o contexto de oficina com base na narrativa fornecida.

# Projeto QA - Postman + Fake REST API

Este projeto foi feito para praticar o uso do Postman em cenários de QA, usando a [Fake REST API](https://fakerestapi.azurewebsites.net/index.html).

## O que foi estudado:
- Variáveis de ambiente (`{{base_url}}`, `activities_id`, `new_activity_id`)
- Collections e organização de requisições
- Scripts de pré-requisição (geração dinâmica de dados)
- Scripts de teste (`pm.test`, `pm.expect`)
- Reaproveitamento de dados entre requisições
- Execução de fluxo completo (CRUD) com o Runner

## Estrutura
- **Collection**: `FakeRestAPI-Projeto-QA.postman_collection.json`
- **Environment**: `FakeRestAPI-Local.postman_environment.json`

## Fluxo demonstrado
1. Criar atividade (POST)
2. Buscar atividade (GET)
3. Atualizar atividade (PUT)
4. Deletar atividade (DELETE)

## Como usar
1. Importe a Collection e o Environment no Postman
2. Selecione o ambiente `FakeRestAPI-Local`
3. Rode a Collection no Runner

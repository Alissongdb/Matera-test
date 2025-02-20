# Teste Técnico Matera

Este repositório é referente ao teste técnico realizado na Matera. O objetivo do teste é demonstrar as habilidades e conhecimentos em automação de testes, criacao de casos de testes tanto front-end quanto para o back-end e registro de defeitos.

## Estrutura do Repositório

O repositório está dividido em diferentes seções, conforme abaixo:

- **Casos de Testes de Front-end**: testes-front
- **Casos de Testes de Back-end**: testes-back
- **Automação de API**: automacao/breeeds.robot

## Tecnologias Utilizadas

- **Robot Framework**: Utilizado para automação de testes de API, garantindo que os endpoints da aplicação respondam conforme esperado.
- **RequestsLibrary**: Biblioteca do Robot Framework usada para realizar requisições HTTP e validar as respostas da API.


## Como Executar os Testes

### Testes de back-end (robot)

Para rodar os testes de back-end, você precisa ter o Robot instalado. Execute os seguintes comandos para instalar e rodar os testes:

pip install robotframework
pip install robotframework-requests
robot breeds.robot


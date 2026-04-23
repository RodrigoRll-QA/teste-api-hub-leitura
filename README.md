# Automação de Testes de API - Hub de Leitura 📚

![QA](https://img.shields.io/badge/Status-Estudo_QA-green?style=flat-square)
![EBAC](https://img.shields.io/badge/Origin-EBAC_Automation-blue?style=flat-square)
![Postman](https://img.shields.io/badge/Tools-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![JavaScript](https://img.shields.io/badge/Language-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node](https://img.shields.io/badge/Runtime-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)

Este repositório contém a automação de testes de API desenvolvida para o projeto Hub de Leitura. O objetivo é validar o ciclo de vida completo de um livro no sistema (CRUD).

## 🚀 Tecnologias Utilizadas
* [Postman](https://www.postman.com/) - Ferramenta de testes de API.
* JavaScript - Scripts de pré-requisição e testes de resposta.
* JSON - Formato de intercâmbio de dados e massa de testes.

## 🧪 Cenários de Teste Implementados
1. **Cadastrar Livros (POST):** Criação de registros com massa de dados dinâmica (`$randomInt`, `$randomAdjective`). Captura e salvamento automático de IDs e ISBNs em variáveis de ambiente.
2. **Listar Livros com Filtros (GET):** Validação de busca por categoria e autor, garantindo que o contrato da API (`author`, `category`) seja respeitado.
3. **Editar Livro (PUT):** Atualização de dados de livros existentes utilizando IDs dinâmicos.
4. **Excluir Livro (DELETE):** Limpeza de registros e validação de códigos de status (200, 204 e tratamento de 404).

## 📋 Como Executar os Testes
1. Faça o download da **Collection** e do **Environment** presentes neste repositório.
2. Importe ambos no seu Postman.
3. Certifique-se de que o ambiente (Environment) está selecionado.
4. Utilize o **Collection Runner** para executar todos os testes em sequência.

---
**Autor:** [Rodrigo Lins] 
*Analista de QA em transição de carreira | EBAC
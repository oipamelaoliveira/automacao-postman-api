# Automação de Testes de API - JSONPlaceholder

Este projeto demonstra a automação de testes funcionais de API utilizando o **Postman**. O foco foi validar as respostas dos endpoints de usuários da API pública JSONPlaceholder.

## Tecnologias utilizadas
* **Postman** (Ferramenta de testes de API)
* **JavaScript** (Scripts de validação)
* **JSONPlaceholder** (API mock para testes)

## O que foi testado?
- **Status code:** Validação global (nível de Collection) para garantir que todos os endpoints retornam `200 OK`.
- **Integridade de dados:** Verificação se os nomes dos usuários retornados correspondem aos IDs solicitados (IDs 1 e 8).
- **Performance:** Verificação se o tempo de resposta é aceitável.

## Como rodar o projeto
1. Baixe os arquivos `.json` deste repositório.
2. No Postman, clique em **Import** e selecione os arquivos.
3. Configure a variável global `url_base` ou importe o arquivo de globals.
4. Clique com o botão direito na coleção e selecione **Run Collection**.

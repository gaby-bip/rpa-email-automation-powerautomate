# RPA Email Automation - Power Automate

Automação desenvolvida em Power Automate Desktop para leitura de um arquivo CSV, filtragem de destinatários por dia da semana e envio automático de e-mails pelo Gmail Web.

## Objetivo

O robô lê uma base CSV com e-mails e dias da semana, identifica o dia atual, filtra os destinatários correspondentes e realiza o envio automático de mensagens.

## Tecnologias utilizadas

- Power Automate Desktop
- Gmail Web
- CSV
- Automação de interface web

## Lógica da automação

1. Ler arquivo CSV
2. Obter data e hora atual
3. Converter a data para o dia da semana
4. Criar lista de e-mails do dia
5. Percorrer os registros do CSV
6. Validar se o dia da linha é igual ao dia atual
7. Adicionar o e-mail correspondente em uma lista
8. Abrir o Gmail no navegador
9. Preencher destinatário, assunto e corpo
10. Enviar e-mail automaticamente

## Conceitos praticados

- Variáveis
- Listas
- For Each
- If/Else
- Leitura de arquivos CSV
- Manipulação de data e hora
- Automação web
- Envio automático de e-mails

## Exemplo de CSV

```csv
email;dia
exemplo1@email.com;Monday
exemplo2@email.com;Tuesday
exemplo3@email.com;Thursday

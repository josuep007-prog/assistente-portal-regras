# Regras do Assistente do Portal do Cliente — ControlTax

A extensão "Assistente do Portal do Cliente" baixa o arquivo [regras.json](regras.json) deste repositório para saber quais campos preencher, quais textos mostrar, quais prazos conferir e quais documentos reconhecer.

**Link usado pela extensão:**
https://raw.githubusercontent.com/josuep007-prog/assistente-portal-regras/main/regras.json

## Como publicar uma mudança

1. Teste a mudança no rules/regras.json da pasta da extensão (modo dev).
2. Substitua o regras.json daqui pela versão testada e aumente o campo "versao".
3. Os clientes recebem em até 30 minutos (ou ao abrir o Chrome).

Se o arquivo daqui estiver com erro, a extensão ignora e continua usando a última versão boa.

Este repositório contém apenas regras e textos — nenhum dado de cliente.

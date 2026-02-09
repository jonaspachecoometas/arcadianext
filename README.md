# Configuração de Frontend

Este repositório armazena as alterações de configuração do frontend em forma de scripts de banco de dados.

## Como funciona

Todas as alterações relacionadas ao frontend são persistidas no banco de dados, principalmente nas definições de **DocType**.

Essas alterações ficam salvas nos arquivos SQL dentro da pasta `db`.

## Como aplicar as alterações

Para aplicar as configurações de frontend em outro ambiente ou projeto:

1. Acesse a pasta `db`.
2. Execute o arquivo SQL no banco de dados do projeto de destino (ex.: banco do ERP Frappe).
3. Após a execução, as configurações de frontend estarão disponíveis automaticamente no sistema.

Não é necessário realizar build ou deploy de frontend.

## Observações

- Sempre que houver alteração no frontend, o script de banco deve ser atualizado.
- Este repositório serve apenas para versionamento e reaplicação das configurações.

# Bot de Liberação de ID

Bot simples e organizado para liberar/revogar whitelist de IDs no banco do seu servidor (FiveM).

## Requisitos
- Node.js 18.17+
- MySQL acessível
- Token de bot do Discord

## Instalação
1) npm i
2) Copie `.env.example` -> `.env` e preencha
3) Ajuste `dbmap.json` se usar outra tabela/coluna
4) npm start

## Configuração no Discord
- /configurar log canal:#logs
- /configurar staff cargo:@Staff

## Comandos
- /liberar id:<número> motivo:[texto]
- /revogar id:<número> motivo:[texto]
- /status id:<número>

## Dicas
- Se “Nenhuma linha afetada”: confira se o ID existe e as queries do `dbmap.json`.
- Se erro de conexão: revise variáveis do `.env`.

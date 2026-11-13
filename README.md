# meusjurosestaoaltos.com.br

Calculadora de juros abusivos: o visitante responde 4 perguntas (tipo de dívida, valor emprestado, parcela e número de parcelas) e a página compara os juros do contrato com a média do Banco Central. No fim, um botão leva para o WhatsApp com o resultado já preenchido.

É uma página única (`index.html`), sem build e sem dependências. Cada push na branch `main` publica automaticamente no Vercel.

## Manutenção mensal

As médias do Banco Central ficam no topo do script, no objeto `MOD` (campo `aa`, em % ao ano). Todo mês:

1. Atualize os valores de `aa` com a nota de Estatísticas Monetárias e de Crédito do Banco Central.
2. Atualize o mês em `REF` e no texto do rodapé.

## Contatos

`WHATSAPP` e `TELEFONE`, também no topo do script.

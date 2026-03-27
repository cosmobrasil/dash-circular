# Dashboard de Distrito Circular

Dashboard HTML para consolidar indicadores e visualizar o relatorio HTML gerado pelo formulario logo apos o envio.

## O que esta incluido
- Filtros por setor, produto, cidade, UF e periodo.
- KPIs de volume, pontos, IGC e PCM.
- Graficos de apoio para analise rapida.
- Lista de relatorios recentes com preview inline do HTML salvo em `questionarios.relatorio_html`.

## Backend esperado
- `GET /api/dashboard/filters`
- `GET /api/dashboard/overview`
- `GET /api/admin/respostas`
- `GET /api/admin/respostas/:id/html`

## Observacao
Se o backend exigir autenticao para os endpoints admin, informe o token no proprio painel.

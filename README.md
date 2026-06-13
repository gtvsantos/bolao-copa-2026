# Bolão Copa 2026 — Painel ao Vivo

Painel web do bolão da Copa do Mundo 2026: placar ao vivo via API pública da ESPN, pontuação automática e ranking dos participantes.

🔗 **Acesse:** https://gtvsantos.github.io/bolao-copa-2026/

## Como funciona

- **[`index.html`](index.html)** — painel completo, página única, sem backend. Os palpites estão embutidos no próprio arquivo (`const DADOS`): apenas nomes dos participantes e seus palpites.

O placar é buscado em tempo real de `site.api.espn.com` e a pontuação é calculada no navegador. Atualiza automaticamente a cada 5 minutos.

> As planilhas de origem (`.xlsx`/`.csv`) são mantidas apenas localmente e não fazem parte deste repositório público.

## Publicação

Hospedado no GitHub Pages a partir da branch `main`, pasta raiz (`/`).

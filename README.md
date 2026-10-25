# Rise — página pública, dados e downloads

Repositório público do Rise, um app de coach para League of Legends. O código do app fica num repositório privado (`lol-companion`); aqui fica só o que precisa ser público:

| O quê | Onde | Quem escreve |
|---|---|---|
| Página do produto | `index.html`, `terms.html`, `privacy.html`, `img/` → https://lucaskarsten.github.io/rise-lol/ | à mão |
| Verificação da Riot | `riot.txt` | à mão (portal da Riot) |
| Números do elo alto (winrates, matchups, builds, pesos da nota) | `data/` → https://lucaskarsten.github.io/rise-lol/data/ | o app que coleta (`RISE_PUBLICAR` no `.env`), sem ids de jogadores nem de partidas |
| Instalador do Windows e atualizações | [Releases](https://github.com/lucaskarsten/rise-lol/releases) | `npm run release` no lol-companion |

O botão "Download for Windows" da página aponta para o último release; o app instalado se atualiza pelos releases daqui.

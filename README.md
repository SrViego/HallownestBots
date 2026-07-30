# Hallownest Bots

Monorepo / índice dos bots do hall.

| Pasta | Repo | Função |
|-------|------|--------|
| [Morgana](./Morgana) | [SrViego/Bot](https://github.com/SrViego/Bot) | Discord — economia, padaria, Pokémon, música |
| [Quirrel](./Quirrel) | [SrViego/Quirrel](https://github.com/SrViego/Quirrel) | Companhia **local** (terminal) |
| [LiveBot](./LiveBot) | [SrViego/LiveBot](https://github.com/SrViego/LiveBot) | Chat **Twitch** multi-jogo + OBS |

## Clonar tudo

```bash
git clone --recurse-submodules https://github.com/SrViego/HallownestBots.git
cd HallownestBots
```

Se já clonaste sem submodules:

```bash
git submodule update --init --recursive
```

## Estrutura

```
HallownestBots/
  Morgana/   → submodule → SrViego/Bot
  Quirrel/   → submodule → SrViego/Quirrel
  LiveBot/   → submodule → SrViego/LiveBot
  README.md
```

Cada bot tem o seu `.env` (nunca commitado).

🕯️

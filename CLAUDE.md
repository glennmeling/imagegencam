# CLAUDE.md

ImageGenCam: DIY-digitalkamera bygget fra OpenAIs referanseprosjekt (egen fork av openai/imagegencam, openai.com/imagegencam). 3D-printet skall, maker-deler og en companion-webapp. Bygges for læring.

`AGENTS.md` er den autoritative kilden for hvordan kameraet bygges, konfigureres og kjøres. Importeres her:

@AGENTS.md

## Git (fork)

Dette repoet er en fork:

- `origin` = `glennmeling/imagegencam` (vår fork, pushbar). Push egne endringer hit som vanlig.
- `upstream` = `openai/imagegencam` (OpenAIs original). Hent oppdateringer derfra med:

```
git fetch upstream && git merge upstream/main
```

`LICENSE` og `README.md` er OpenAIs og beholdes uendret. Egen dokumentasjon (denne fila) ligger på toppen av OpenAIs historikk.

## Status

Læringsprosjekt, stabilt. Dette dokumentet er kun en inngangsport; alt det praktiske ligger i `AGENTS.md`.

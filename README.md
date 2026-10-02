# Rapport de Projet — AWS Next Express (PFA)

Rapport de projet académique (LaTeX) — *Développement d'une Application Full-Stack avec Méthodologie Scrum*.

Application full-stack Next.js déployée sur AWS (DynamoDB, S3, Docker, Kubernetes) avec pipeline DevOps.

## Contenu

| Fichier / dossier | Description |
|---|---|
| `main.tex` | Document principal (mise en page, styles, sommaire) |
| `sections/` | Chapitres : page de titre, introduction, contexte, méthodologie Scrum, architecture technique, implémentation, DevOps, tests, résultats, conclusion, annexes (code, config), bibliographie |

## Compilation

```bash
pdflatex main.tex
bibtex main          # si références bibliographiques
pdflatex main.tex
pdflatex main.tex
```

Ou utilisez un éditeur LaTeX en ligne (Overleaf) : importez le dépôt et compilez `main.tex`.

## Auteurs

- Nour el Houda Bouajila
- Ghofrane Nasri

# Decisions

## 2026-10-23 — Mémoire projet dans `aidocs/`

`docs/` est réservé à la doc publiée du site (Jekyll publie le contenu du repo).
Donc handoff, log, décisions et runbook vivent dans `aidocs/`, exclu du build.

## 2026-10-23 — Pas de build local pour l'instant

Jekyll est compilé par GitHub Pages. On n'ajoute un Gemfile que si le besoin de prévisualiser en local apparaît.

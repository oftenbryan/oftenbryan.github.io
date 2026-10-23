# Runbook

## Git

```powershell
git status
git add -A
git commit -m "message"
git push
```

Push sur `main` = déploiement GitHub Pages (1-2 min).

## Preview locale (optionnel, pas encore installé)

```powershell
gem install jekyll bundler
jekyll serve
```

## MCP Decode

Config : `~/.config/opencode/opencode.json` (entrée `decode`, `http://localhost:9876/mcp`).
L'app Decode doit tourner avec un board ouvert, sinon la connexion échoue.

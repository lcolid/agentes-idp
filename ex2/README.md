# Exercício 1.2 — GitHub CLI

Evidência do exercício 1.2: uso do `gh` para automatizar a criação de um Pull Request.

Fluxo executado:

1. `git checkout -b feat/ex2-github-cli`
2. Criação deste arquivo e commit
3. `git push -u origin feat/ex2-github-cli`
4. `gh pr create --title "..." --body "..."`
5. `gh pr merge --squash --delete-branch`

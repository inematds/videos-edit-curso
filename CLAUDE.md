# CLAUDE.md — videos-edit-curso

Curso completo "Forja Reel" (4 trilhas, navegável). Ver [[videos-edit-cria]]
pra skill em si (download + guia de uso) — repo irmão, separado deste em
2026-07-17 (antes eram um único repo `videos-edit`).

## Git / autor

Este repo vive na conta GitHub **`inematds`**.

- `git config` (local) = `inematds <inematds@gmail.com>`.
- Remote: `git@github.com:inematds/videos-edit-curso.git`.
- Repo novo (clone com histórico do antigo `videos-edit`, que virou
  `videos-edit-cria`) — não confundir com aquele.

## Estrutura

- `curso/trilha1..4/` — o curso em si (formato-curso-v2, manifesto no `<head>`).
- `index.html` — landing do curso, na raiz (padrão antigo de curso, não o
  padrão `guia/` de projeto).
- `assets/learn.css` + `assets/learn.js` — camada de aprendizagem compartilhada.
- Download da skill (`.skill`) não fica mais aqui — os 3 botões de download
  apontam pro guia em `videos-edit-cria` (`https://inematds.github.io/videos-edit-cria/guia/`).

## Deploy = sempre via git

Publicar = `commit + push` no `origin`. GitHub Pages via Actions
(`build_type=workflow`, não legacy). Deploy automático — não cutucar
dashboard/status.

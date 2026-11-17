# FZL Apps — wagnermarques.github.io

Página inicial, política de privacidade e termos compartilhados pelos aplicativos FZL
que usam o mesmo cliente OAuth Google.

- `privacidade.html` é uma cópia de `privacy.html` (o Google Auth Platform aponta para ela).
  Ao editar a política, regenere: `sed 's#<link rel="stylesheet" href="style.css" />#&\n    <link rel="canonical" href="https://wagnermarques.github.io/privacy.html" />#' privacy.html > privacidade.html`
- `googlec90fa1f80e168db2.html`: verificação do Google Search Console — não remover.
- Novo app: adicionar em `apps.js`.

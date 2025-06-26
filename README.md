# 🚀 Khanware Bookmarklet

Script para usar o **Khanware** direto do seu navegador, sem instalar nada!

---

## ✅ Como usar

1. Crie um novo favorito no seu navegador.
2. No campo de URL, cole **exatamente** este código:
3. Logo após pesquisa o nome que você colocou depois de copiar o link

```js
javascript:fetch("https://cdn.jsdelivr.net/gh/YAGO-CAVALLI/Khanware-Bookmarklet@main/Khanware.js").then(t=>t.text()).then(eval);

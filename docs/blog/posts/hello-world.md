---
draft: true 
date: 2024-01-31 
categories:
  - Hello
  - World
---

# Hello world!

**Recap** delle cose da **sistemare**:

1. Come caricare correttamente le immagini :warning:
2. Come si ridimensiona una foto 







<!-- Aggiungi il link al CSS di Gitalk -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gitalk/dist/gitalk.css">

<!-- Sezione di commenti -->
<div id="gitalk-container"></div>

<!-- Aggiungi il codice per caricare Gitalk -->
<script src="https://cdn.jsdelivr.net/npm/gitalk@latest/dist/gitalk.min.js"></script>
<script>
  var gitalk = new Gitalk({
    clientID: 'YOUR_CLIENT_ID',       // Inserisci il Client ID ottenuto da GitHub
    clientSecret: 'YOUR_CLIENT_SECRET', // Inserisci il Client Secret ottenuto da GitHub
    repo: 'YOUR_REPOSITORY',           // Inserisci il nome del repository creato (ad esempio 'comments')
    owner: 'YOUR_GITHUB_USERNAME',     // Il tuo username GitHub
    admin: ['YOUR_GITHUB_USERNAME'],   // La lista degli amministratori (puoi mettere il tuo username)
    id: location.pathname,             // Usa il percorso URL per identificare i commenti (ad esempio: /blog/post1)
    distractionFreeMode: false,        // Attiva/disattiva la modalità senza distrazioni
    language: 'it'                     // Imposta la lingua
  });

  // Avvia Gitalk
  gitalk.render('gitalk-container');
</script>



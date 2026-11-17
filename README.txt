ATHLETIC 180 — Prototype PWA V1

Contenu :
- index.html : interface
- style.css : design responsive sombre
- app.js : calendrier, séances, coches, suivi des données
- manifest.webmanifest et sw.js : installation PWA et cache hors connexion

Démarrage local :
1. Décompresser le dossier.
2. Pour tester, lancer un serveur HTTP local depuis ce dossier (par exemple : python -m http.server 8000).
3. Ouvrir http://localhost:8000.

Installation iPhone :
1. Publier le dossier sur un hébergement HTTPS statique.
2. Ouvrir l'URL dans Safari.
3. Partager > Sur l'écran d'accueil.
4. Ouvrir une première fois avec Internet pour mettre les fichiers en cache.

Limites V1 :
- Les données sont stockées localement dans le navigateur (localStorage) et ne sont pas synchronisées.
- Export JSON manuel disponible.
- Les repas sont des exemples de structure, pas encore un menu complet calculé recette par recette.
- Le calendrier présente une semaine type répétée ; la périodisation détaillée doit être injectée dans la version suivante.
- Les données Apple Santé ne sont pas importées automatiquement.

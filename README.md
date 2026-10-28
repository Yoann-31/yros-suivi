# yros-suivi

Page de suivi en direct de l'app YROs (position partagée, SOS), publiée par GitHub Pages.

Elle ne contient aucune donnée ni aucun secret. Le lien reçu par SMS porte, après le `#`, l'identifiant
du script Google du propriétaire et celui du partage : cette partie du lien n'est jamais envoyée à GitHub.
La page lit la position en JSON chez ce script, sans cookies, ce qui évite l'erreur Google
« Impossible d'ouvrir le fichier » des navigateurs connectés à plusieurs comptes.

La source de cette page est `suivi/index.html` dans le dépôt de l'app : la modifier là-bas, puis la recopier ici.

---
title: Accueil
playground: true
---
# Bouton mode sombre pour Cecil

Ce site est la démo du [thème composant _Dark mode toggle_](https://github.com/Cecilapp/theme-darkmodetoggle) pour [Cecil](https://cecil.app).

Cliquez sur la **lune** (ou le **soleil**) dans l'en-tête, ou sur le gros bouton ci-dessous, pour basculer entre les modes clair et sombre :

- votre choix est mémorisé, jusqu'à ce qu'il corresponde de nouveau à la préférence de votre système ;
- changez le mode de couleur de votre système : la page le suit ;
- rechargez la page : aucun flash du mauvais mode de couleur.

Le gros bouton est le même partial, personnalisé avec des propriétés CSS, et les boutons ci-dessous utilisent l'API JavaScript (`window.colorScheme.set()`).

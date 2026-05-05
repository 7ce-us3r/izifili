# Izifili<span>.</span>

<p align="center">
  <img src="favicon.png" alt="Izifili Logo" width="100"/>
</p>

> **Filigrane Gratuit, Sécurisé et 100% Local.**

Izifili est un outil web ultra-simple conçu pour protéger la confidentialité de vos documents sensibles (carte d'identité, justificatifs, photos) avant de les envoyer.

**Le problème :** La plupart des outils de filigrane en ligne vous obligent à télécharger vos documents sur leurs serveurs. Vous ne savez pas ce qu'il advient de vos données personnelles.

**La solution Izifili :** Vos documents ne quittent JAMAIS votre ordinateur. Tout le traitement est effectué localement dans votre navigateur grâce au JavaScript.

<p align="center">
  <a href="https://izifili.com"><strong> Essayer Izifili.com</strong></a>
</p>

---

## Confidentialité par Design (Zéro-Log)

Izifili est une démonstration technique de ce qu'il est possible de réaliser en "Client-Side" pur pour respecter la vie privée (RGPD compliant).

   **Aucun upload serveur.**
   **Aucun stockage de données.**
   **Aucun cookie de traçage.**
   **Fonctionne hors ligne** (une fois la page chargée).

## Fonctionnalités

   **Support multi-format :** PDF, PNG, JPEG.
   **Filigrane personnalisé :** Texte libre.
   **Design Anti-IA :** Le filigrane utilise une grille maillée dense et des lignes d'interférence pour compliquer la tâche des algorithmes de suppression par IA.
   **Multilingue :** Français 🇫🇷, Anglais 🇺🇸, Allemand 🇩🇪.
   **Théming :** Mode Sombre et Mode Clair.
   **Nommage intelligent :** Les fichiers sécurisés sont renommés avec le préfixe `izifili_`.

## Stack Technique

Ce projet est volontairement minimaliste et tient dans un seul fichier HTML/CSS/JS, prouvant la puissance du web moderne :

   **HTML5 / CSS3** (Variables CSS pour le théming).
   **JavaScript Vanilla** (Manipulation de Canvas, File API, i18n).
   **[pdf-lib.js](https://github.com/Hopding/pdf-lib)** (chargée via CDN) : Pour la manipulation directe de documents PDF dans le navigateur.

## Installation & Déploiement

Comme le projet est un site statique en un seul fichier, il est extrêmement facile à héberger.

1.  Téléchargez le dépôt.
2.  Ouvrez `index.html` dans votre navigateur pour tester localement.
3.  Pour le mettre en ligne, glissez-déposez le dossier sur **Cloudflare Pages** (recommandé), GitHub Pages, ou n'importe quel hébergeur statique.

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE] pour plus de détails.
---
title: API DE RECOMMANDATION INTELLIGENTE
publishDate: 2020-03-02 00:00:00
img: /assets/apir.png
img_alt: Iridescent ripples of a bright blue and pink liquid
description: |
  We designed a whodunnit-style game to introduce Markdown formatting. Suspense — suspicion — syntax!
tags:
  - Angular
  - Flask
  - K-Means
  - Intégration d'API
---

## RESUME DU PROJET
Ce rapport présente notre projet de fin d'etude d'ingenieur "API de Recommandation Intelligente" au sein de ProTech-IT. En exploitant le traitement de texte, l'apprentissage automatique et le regroupement (K-means), notre solution client-serveur, élaborée avec Angular et Flask, génère des recommandations d'emploi personnalisées. Les utilisateurs fournissent leurs profils, déclenchant notre modèle K-means pour des recommandations pertinentes. L'intégration sécurisée de Firebase renforce l'authentification. Ce projet révèle notre compétence en programmation, conception d'interfaces et déploiement, avec des perspectives d'améliorations et d'expansion à venir.

## Galerie d'images

<div class="image-grid">
  <div class="image-item">
    <img src="/assets/dw1.png" alt="Description de l'image 1">
  </div>
  <div class="image-item">
    <img src="/assets/dw2.png" alt="Description de l'image 2">
  </div>
  <div class="image-item">
    <img src="/assets/dw3.png" alt="Description de l'image 3">
  </div>
  <div class="image-item">
    <img src="/assets/dw4.png" alt="Description de l'image 3">
  </div>

  <!-- Ajoutez d'autres images ici -->
</div>

<style>
  .image-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); /* Répartition automatique des colonnes avec une largeur minimale de 250px */
  grid-gap: 20px; /* Espace entre les images */
}

.image-item {
  position: relative;
  overflow: hidden;
}

.image-item img {
  display: block;
  width: 100%;
  height: auto;
  transition: transform 0.3s ease; /* Transition fluide pour l'effet de survol */
}

.image-item:hover img {
  transform: scale(1.1); /* Zoom de 10% sur l'image au survol */
}

@media screen and (max-width: 768px) {
  .image-grid {
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); /* Réduire la taille des colonnes pour les appareils mobiles */
    grid-gap: 15px; /* Réduire l'espace entre les images */
  }
}

</style>
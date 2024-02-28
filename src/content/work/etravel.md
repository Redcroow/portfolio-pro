---
title: E-Travel
publishDate: 2023-07-01 00:00:00
img: /assets/work/etravel.png
img_alt: E-Travel index
description: |
tags:
  - NextJS
  - NestJS
  - Docker
  - Scss
---

### Projet Fil Rouge : E-Travel
<br><br>

##### Introduction
Ce document présente le projet E-Travel, réalisé dans le cadre du Master 1 Expert en système informatique à l'école Ingetis Paris. Ce projet fil rouge, mené sur une année, s'inscrit dans une démarche pédagogique innovante visant à mettre les étudiants en situation réelle de création de start-up.
<br><br>

##### Rôle et équipe
J'ai occupé les postes de chef de projet et de lead développeur front-end au sein d'une équipe de 3 étudiants.
<br><br>

##### Objectifs
E-Travel a pour objectif de simplifier la planification de voyages en proposant une plateforme tout-en-un pour :
- Visualiser les billets d'avion, les hébergements et les activités.
- Comparer les prix des vols et des hébergements pour trouver les meilleures offres.
- Planifier l'intégralité du voyage, de A à Z.
- Prévisualiser l'itinéraire même en cas de connexion internet défaillante.
<br><br>

##### Outils et technologies
Le projet E-Travel a été développé en utilisant les outils et technologies suivants :
- Méthodologie agile: Trello (Kanban)
- Hébergement: Azure
- Base de données: Metabase
- Front-end: Next.js, React
- Back-end: Nest.js
<br><br>

##### Synopsie
E-Travel vous facilite la planification de votre voyage en vous proposant un système intégré de visualisation pour les billets d'avion, le logement et les activités, avec des comparateurs de prix pour les vols et le logement pour économiser de l'argent. Vous pouvez planifier votre voyage de A à Z avec une prévisualisation d'itinéraire disponible en cas de défaut d'internet.
<br><br>

##### Remarques
Ce document est un résumé du projet. Le projet n'est acutellement plus hébergé.
Le code source du projet est disponible sur [GitHub](https://github.com/ProximaPolaris/etravel).
<br><br>

##### Maquettage

<div class="section-maquettage">
  <div class="slider" id="slider">
    <div class="slide">
      <img src="../../../public/assets/maquettage/maquettage1.png" alt="Image 1" class="img-voyage">
    </div>
    <div class="slide">
      <img src="../../../public/assets/maquettage/maquettage2.png" alt="Image 2" class="img-voyage">
    </div>
    <div class="slide">
      <img src="../../../public/assets/maquettage/maquettage3.png" alt="Image 3" class="img-voyage">
    </div>
        <div class="slide">
      <img src="../../../public/assets/maquettage/maquettage4.png" alt="Image 3" class="img-voyage">
    </div>
        <div class="slide">
      <img src="../../../public/assets/maquettage/maquettage5.png" alt="Image 3" class="img-voyage">
    </div>
        <div class="slide">
      <img src="../../../public/assets/maquettage/maquettage6.png" alt="Image 3" class="img-voyage">
    </div>
        <div class="slide">
      <img src="../../../public/assets/maquettage/maquettage7.png" alt="Image 3" class="img-voyage">
    </div>
        <div class="slide">
      <img src="../../../public/assets/maquettage/maquettage8.png" alt="Image 3" class="img-voyage">
    </div>
        <div class="slide">
      <img src="../../../public/assets/maquettage/maquettage9.png" alt="Image 3" class="img-voyage">
    </div>
        <div class="slide">
      <img src="../../../public/assets/maquettage/maquettage10.png" alt="Image 3" class="img-voyage">
    </div>
        <div class="slide">
      <img src="../../../public/assets/maquettage/maquettage11.png" alt="Image 3" class="img-voyage">
    </div>
        <div class="slide">
      <img src="../../../public/assets/maquettage/maquettage12.png" alt="Image 3" class="img-voyage">
    </div>
</div>

<style>
.section-maquettage {
  overflow: hidden;
}

.slider {
  display: flex;
  align-items: center;
  animation: scrollImages 40s linear infinite;
  gap: 20px;
  @media screen and (min-width: 1200px) {
    animation: scrollImages 50s linear infinite;
  }
}

.slide {
  flex-shrink: 0;
  width: 90%;
  @media screen and (min-width: 1200px) {
    width: 50%;
  }
}

@keyframes scrollImages {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(-1100%);
  }
}

@media screen and (min-width: 1200px) {
  @keyframes scrollImages {
    100% {
      transform: translateX(-600%);
    }
  }
}

</style>
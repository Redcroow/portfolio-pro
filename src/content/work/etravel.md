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

##### Introduction
This document presents the E-Travel project, carried out as part of the Master 1 IT Systems Expert course at Ingetis Paris. This year-long project is part of an innovative teaching approach designed to put students in real-life start-up situations.
<br><br>

##### Role and team
I was project manager and front-end lead developer in a team of 3 students.
<br><br>

##### Targets
E-Travel aims to simplify travel planning by offering an all-in-one platform for :
- View flight tickets, accommodation and activities.
- Compare flight and accommodation prices to find the best deals.
- Plan your entire trip, from A to Z.
- Preview your itinerary even if your internet connection is down.
<br><br>

##### Tools and technologies
The E-Travel project was developed using the following tools and technologies:
- Agile methodology: Trello (Kanban)
- Hosting: Azure
- Database: Metabase
- Front-end: Next.js, React
- Back-end: Nest.js
<br><br>

##### Synopsy
E-Travel makes it easy for you to plan your trip by offering an integrated viewing system for flight tickets, accommodation and activities, with price comparators for flights and accommodation to save you money. You can plan your trip from A to Z with an itinerary preview available in the event of internet failure.
<br><br>

##### Appendices
This document is a summary of the project. The project is currently no longer hosted.
The project source code is available on [GitHub](https://github.com/ProximaPolaris/etravel).
<br><br>

##### Design

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
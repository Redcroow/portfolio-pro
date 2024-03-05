---
title: Shopify Hub
publishDate: 2024-04-30 00:00:00
img: /assets/work/bo-shopifyHub.png
img_alt: Shopify hub index
description: |
tags:
- Java (Spring Boot)
- Hilla (react)
- Typescript
---

##### Introduction
This document presents the Shopify Hub project, carried out as part of the Master 2 IT Systems Expert course at Ingetis
Paris. This project was carried out in collaboration with the company COGENIO under a work-study contract.
<br><br>

##### Targets
The Shopify Hub project aims to :
- Develop a back office for the Cashville website, a streetwear e-commerce site.
- Implement CRUD (Create, Read, Update, Delete) functions for managing colours and sizes.
- Have a system that filters and displays logs for all services: Fastmag, Bigcommerce, Jobs, Shopify.
- Enable stock and inventory management for Cashville's physical shops as well as B2, formerly Stergan, another
streetwear e-commerce site.
<br><br>

##### Technology
The Shopify Hub project was developed using the following technologies:
- Back-end: Java Spring Boot
- Front-end: Hilla (Vaadin)
<br><br>

##### Conclusion
The Shopify Hub project is a comprehensive, high-performance tool for managing Cashville's back office and centralising
stocks and inventories for its various shops. The project has been developed using modern technologies and meets the
company's specific needs.
<br><br>

##### Appendices
<div style="  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;">
  <div class="container">
    <input type="radio" name="slider" id="item-1" checked>
    <input type="radio" name="slider" id="item-2">
    <input type="radio" name="slider" id="item-3">
    <div class="cards">
      <label class="card" for="item-1" id="bo-1">
        <img src="../../../public/assets/work/appendice-bo1.png" alt="bo">
      </label>
      <label class="card" for="item-2" id="bo-2">
        <img src="../../../public/assets/work/appendice-bo2.png" alt="bo">
      </label>
      <label class="card" for="item-3" id="bo-3">
        <img src="../../../public/assets/work/appendice-bo3.png" alt="bo">
      </label>
    </div>
  </div>
</div>
<style>
  * {
    box-sizing: border-box;
  }
  input[type=radio] {
    display: none;
  }
  .card {
    position: absolute;
    width: 85%;
    left: 0;
    right: 0;
    margin: auto;
    transition: transform .4s ease;
    cursor: pointer;
  }
  .container {
    display: flex;
    justify-content: space-between;
    transform-style: preserve-3d;
    width: 100%;
    height: 350px;
    position: relative;
  }
  .cards {
    margin-bottom: 20px;
  }
  img {
    width: 100%;
    height: 100%;
    border-radius: 10px;
    object-fit: cover;
  }
  #item-1:checked~.cards #bo-3,
  #item-2:checked~.cards #bo-1,
  #item-3:checked~.cards #bo-2 {
    transform: translatex(-40%) scale(.8);
    opacity: .4;
    z-index: 0;
  }
  #item-1:checked~.cards #bo-2,
  #item-2:checked~.cards #bo-3,
  #item-3:checked~.cards #bo-1 {
    transform: translatex(40%) scale(.8);
    opacity: .4;
    z-index: 0;
  }
  #item-1:checked~.cards #bo-1,
  #item-2:checked~.cards #bo-2,
  #item-3:checked~.cards #bo-3 {
    transform: translatex(0) scale(1);
    opacity: 1;
    z-index: 1;
    img {
      box-shadow: 0px 0px 5px 0px rgba(81, 81, 81, 0.47);
    }
  }
</style>
---
layout: home
title: Home
---
<html lang ="en">
<body>
  {% include navbar.html %}
<main>
    <article data-index="0" data-status="active">
      <div class="article-image-section article-section"></div>
      <div class="article-description-section article-section">
        <p>
          Place holder - description
        </p>
      </div>
      <div class="article-title-section article-section">
        <h2>Title</h2>
        <i class="fa-solid fa-plus"></i>
      </div>
      <div class="article-nav-section article-section">
        <button class="article-nav-button" type="button" onclick="handleLeftClick()">
          <i class="fa-solid fa-arrow-left-long"></i>
        </button>
        <button class="article-nav-button" type="button" onclick="handleRightClick()">
          <i class="fa-solid fa-arrow-right-long"></i>
        </button>
      </div>
    </article>
    <article data-index="1" data-status="inactive">
      <div class="article-image-section article-section"></div>
      <div class="article-description-section article-section">
        <p>Placeholder2 - description</p>
      </div>
      <div class="article-title-section article-section">
        <h2>Wicked Cool Library Shelves</h2>
        <i class="fa-light fa-plus-large"></i>
      </div>
      <div class="article-nav-section article-section">
        <button class="article-nav-button" type="button" onclick="handleLeftClick()">
          <i class="fa-solid fa-arrow-left-long"></i>
        </button>
        <button class="article-nav-button" type="button" onclick="handleRightClick()">
          <i class="fa-solid fa-arrow-right-long"></i>
        </button>
      </div>
    </article>
    <article data-index="2" data-status="inactive">
      <div class="article-image-section article-section"></div>
      <div class="article-description-section article-section">
        <p>The neatest lighthouse you ever saw. Ehh, actually it's kind of messy. But that's why the pic is of the
          outside.</p>
      </div>
      <div class="article-title-section article-section">
        <h2>Neato Toledo Lighthouse</h2>
        <i class="fa-light fa-plus-large"></i>
      </div>
      <div class="article-nav-section article-section">
        <button class="article-nav-button" type="button" onclick="handleLeftClick()">
          <i class="fa-solid fa-arrow-left-long"></i>
        </button>
        <button class="article-nav-button" type="button" onclick="handleRightClick()">
          <i class="fa-solid fa-arrow-right-long"></i>
        </button>
      </div>
    </article>
    <article data-index="3" data-status="inactive">
      <div class="article-image-section article-section"></div>
      <div class="article-description-section article-section">
        <p>
          The blobiest of blobs nestled deep in the heart of outer space. Well, technically the universe is both infinite
          and homogeneous so there isn't really a heart, per se.
        </p>
      </div>
      <div class="article-title-section article-section">
        <h2>Super Space Blob</h2>
        <i class="fa-light fa-plus-large"></i>
      </div>
      <div class="article-nav-section article-section">
        <button class="article-nav-button" type="button" onclick="handleLeftClick()">
          <i class="fa-solid fa-arrow-left-long"></i>
        </button>
        <button class="article-nav-button" type="button" onclick="handleRightClick()">
          <i class="fa-solid fa-arrow-right-long"></i>
        </button>
      </div>
    </article>
  </main>
</body>
</html>
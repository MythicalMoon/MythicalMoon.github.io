---
layout: page
title: About
permalink: /about/
---
<html lang ="en">
<body>
  {% include navbar.html %}
    <main>
        <about data-index="0">
        <div class="about-title-section about-section about-image-section">
            <h2>
            Kaspars S.B.
            </h2>
        </div>
        <div class="about-description-section about-section">
            {%include intro.html%}
            {%include skillset.html%}
            {%include working-on.html%}
        </div>
        </about>
    </main>
</body>
</html>
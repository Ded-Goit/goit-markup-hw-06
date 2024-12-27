goit-markup-hw-06
my home work 6

тег <picture>
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture

<picture>
<source
  srcset="
    ./images/portfolio-img-desk.jpg    1x,
    ./images/portfolio-img-desk@2x.jpg 2x
  "
  media="(min-width: 1158px)"
/>
<source
  srcset="
    ./images/portfolio-img-tab.jpg    1x,
    ./images/portfolio-img-tab-@2x.jpg 2x
  "
  media="(min-width: 768px)"
/>
<source
  srcset="
    ./images/portfolio-img-mob.jpg    1x,
    ./images/portfolio-img-mob-@2x.jpg 2x
  "
  media="(max-width: 767px)"
/>
<img
  src="./images/portfolio-img-mob.jpg"
  alt="portfolio pictxure"
/>
<picture>

# lazysizes-cheat-sheet
Lazysizes cheat sheet


# Download
- https://github.com/aFarkas/lazysizes

<br><br>

## Getting started
```css
iframe{
  background-size: cover;
  background-repeat: no-repeat;
  background-position: 50% 50%;
}
```

```html
<!-- Use class="lazyload" and data-bgset="./images/loading.svg" -->
<iframe data-bgset="./images/loading.svg" class="lazyload" width="560" height="315" src="https://www.youtube.com/embed/X0usZecLFo4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<script src="js/ls.bgset.min.js" defer></script>
<script src="js/lazysizes.min.js" defer></script>
```

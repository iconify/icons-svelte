<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vy8rekb2i"/><path class="q46ar0blg"/><path class="n0xh97d3q"/><path class="fq9fxhble"/><path class="i5z6dbbpo"/><path class="cs6dambue"/><path class="wwozeg7ww"/><path class="yih0nfb7c"/><path class="qxhe48bjs"/><path class="evq885uwk"/><path class="af7iv3n-p"/><path class="x3jkjl77t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:umbrella-open-duotone-regular" {...props}></Icon>
<style>
:global(.af7iv3n-p) {
  d: path("M12 2v2.5");
}

:global(.cs6dambue) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m19 3 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.evq885uwk) {
  d: path("m5 3 2 2");
}

:global(.fq9fxhble) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 3 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i5z6dbbpo) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 2v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n0xh97d3q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 14v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q46ar0blg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 14h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qxhe48bjs) {
  d: path("M12 14v7");
}

:global(.vy8rekb2i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 14a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wwozeg7ww) {
  d: path("M3 14a9 9 0 0 1 18 0");
}

:global(.x3jkjl77t) {
  d: path("m19 3 -2 2");
}

:global(.yih0nfb7c) {
  d: path("M3 14h18");
}

</style>

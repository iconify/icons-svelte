<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rvwkn2b2s"/><path class="c4e1y7wvc"/><path class="a20judcsg"/><path class="tlpz21bnw"/><path class="gyi-tobvb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:unavailable-limit-outline-regular" {...props}></Icon>
<style>
:global(.a20judcsg) {
  d: path("m10.5 10.5 3 3");
}

:global(.c4e1y7wvc) {
  d: path("M4 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.gyi-tobvb) {
  d: path("M20 5v14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rvwkn2b2s) {
  d: path("M2 8a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.tlpz21bnw) {
  d: path("m13.5 10.5 -3 3");
}

</style>

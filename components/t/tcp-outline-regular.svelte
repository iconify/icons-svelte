<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hnwta_3qv"/><path class="bb7inz33j"/><path class="nqnw98byf"/><path class="ydpr20bza"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tcp-outline-regular" {...props}></Icon>
<style>
:global(.bb7inz33j) {
  d: path("M13.5 5a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4.5a2 2 0 0 1 -2 -2Z");
}

:global(.hnwta_3qv) {
  d: path("M2 5a2 2 0 0 1 2 -2h4.5a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.nqnw98byf) {
  d: path("M2 14h20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ydpr20bza) {
  d: path("m7 18 3 3 7 -7");
}

</style>

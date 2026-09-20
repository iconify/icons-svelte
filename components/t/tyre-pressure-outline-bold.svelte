<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r2m9mtdol"/><path class="aymrypeyx"/><path class="evwcdlhbn"/><path class="x0y-s6bwx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tyre-pressure-outline-bold" {...props}></Icon>
<style>
:global(.aymrypeyx) {
  d: path("M7 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.evwcdlhbn) {
  d: path("M14 7a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.r2m9mtdol) {
  d: path("M2.5 15a6.5 6.5 0 1 0 13 0 6.5 6.5 0 1 0 -13 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x0y-s6bwx) {
  d: path("m18 7 2.5 -2.5");
}

</style>

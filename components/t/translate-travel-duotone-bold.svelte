<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ou1kg9jzg"/><path class="chzquvbpx"/><path class="is6npyb7a"/><path class="g_pok7b1i"/><path class="uqbiloglf"/><path class="cgy8y9byr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:translate-travel-duotone-bold" {...props}></Icon>
<style>
:global(.cgy8y9byr) {
  d: path("M17 17v3l3 -3");
}

:global(.chzquvbpx) {
  fill: currentColor;
  d: path("M14 9h8v8h-8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.g_pok7b1i) {
  d: path("M5 13v3l3 -3");
}

:global(.is6npyb7a) {
  d: path("M2 5h8v8H2Z");
}

:global(.ou1kg9jzg) {
  fill: currentColor;
  d: path("M2 5h8v8H2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uqbiloglf) {
  d: path("M14 9h8v8h-8Z");
}

</style>

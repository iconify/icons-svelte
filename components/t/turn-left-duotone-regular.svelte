<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gr-2bmw8s"/><path class="zsdu4_bkp"/><path class="a-wplf-uj"/><path class="wd2ghz3oy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:turn-left-duotone-regular" {...props}></Icon>
<style>
:global(.a-wplf-uj) {
  d: path("M16 21V9H7");
}

:global(.gr-2bmw8s) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 21V9H7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wd2ghz3oy) {
  d: path("M10 6 7 9l3 3");
}

:global(.zsdu4_bkp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 6 7 9l3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a-wplf-uj"/><path class="wd2ghz3oy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:turn-left-outline-regular" {...props}></Icon>
<style>
:global(.a-wplf-uj) {
  d: path("M16 21V9H7");
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

</style>

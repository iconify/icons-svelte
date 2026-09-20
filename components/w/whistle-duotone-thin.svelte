<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iwo9vlwah"/><path class="wajv_y-6p"/><path class="nyo0sgxgn"/><path class="oewjtrp_y"/><path class="jf0dusbyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:whistle-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iwo9vlwah) {
  fill: currentColor;
  d: path("M9 6c4 0 7 3 7 7 0 3 -3 6 -7 6s-6 -3 -6 -6c0 -4 2 -7 6 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jf0dusbyh) {
  d: path("M16 10h5v3h-5");
}

:global(.nyo0sgxgn) {
  d: path("M9 6c4 0 7 3 7 7 0 3 -3 6 -7 6s-6 -3 -6 -6c0 -4 2 -7 6 -7");
}

:global(.oewjtrp_y) {
  d: path("M7 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.wajv_y-6p) {
  fill: currentColor;
  d: path("M7 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

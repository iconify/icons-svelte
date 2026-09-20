<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tvpgdo31a"/><path class="dpvrwwhil"/><path class="iyltd-baj"/><path class="mi_m6achy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:script-run-outline-thin" {...props}></Icon>
<style>
:global(.dpvrwwhil) {
  d: path("M5 9h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iyltd-baj) {
  d: path("M5 13h6");
}

:global(.mi_m6achy) {
  d: path("m17 9 3 3 -3 3");
}

:global(.tvpgdo31a) {
  d: path("M2 6a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>

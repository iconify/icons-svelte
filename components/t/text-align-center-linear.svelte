<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y8rchkbuh"/><path class="w4y0zdb1t"/><path class="zvlywgbxr"/><path class="qtl0xvb8o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-align-center-linear" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qtl0xvb8o) {
  d: path("M7.5 18H16.5");
}

:global(.w4y0zdb1t) {
  d: path("M7.5 10H16.5");
}

:global(.y8rchkbuh) {
  d: path("M5 6H19");
}

:global(.zvlywgbxr) {
  d: path("M5 14H19");
}

</style>

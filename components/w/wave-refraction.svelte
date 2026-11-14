<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nus3ylbxb"/><path class="hou2uebcv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:wave-refraction" {...props}></Icon>
<style>
:global(.hou2uebcv) {
  d: path("m12.5 18.75l3 2.25l1-3.75");
}

:global(.nus3ylbxb) {
  d: path("M2.5 12h19M4 3l8 9l3.5 9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

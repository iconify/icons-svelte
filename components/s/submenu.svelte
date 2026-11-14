<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dt7alwbag"/><path class="leuncbb1o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:submenu" {...props}></Icon>
<style>
:global(.dt7alwbag) {
  d: path("M10.2 16.5H2.5v-14h13v8.7M5.25 6H8.5M5.25 9.5H8.5M5.25 13H8.5");
}

:global(.leuncbb1o) {
  d: path("m11 7.75l1.75 1.75L11 11.25M13 14h8.5v7.5H13Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

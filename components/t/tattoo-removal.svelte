<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yvem4vb7c"/><path class="bugs33b0j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tattoo-removal" {...props}></Icon>
<style>
:global(.bugs33b0j) {
  d: path("m15.75 8.25l3.5-3.5M13.5 6L17 2.5m1 8L21.5 7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yvem4vb7c) {
  fill: currentColor;
  d: path("M3.5 11H13v9.5H3.5Z");
}

</style>

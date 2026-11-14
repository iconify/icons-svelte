<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vica_mbcq"/><path class="nsi6t9b_m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tree-ornament" {...props}></Icon>
<style>
:global(.nsi6t9b_m) {
  fill: currentColor;
  d: path("M10.25 13.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vica_mbcq) {
  d: path("m12 2.5l4.5 7h-2l5 8h-15l5-8h-2Zm0 15v4");
}

</style>

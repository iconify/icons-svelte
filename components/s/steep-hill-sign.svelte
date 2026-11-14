<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nz1gfmbhq"/><path class="t6n9kj4-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:steep-hill-sign" {...props}></Icon>
<style>
:global(.nz1gfmbhq) {
  d: path("m12 2.5l10 19H2Z");
}

:global(.t6n9kj4-o) {
  d: path("M17 18.5H6.75L14 13.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

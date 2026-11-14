<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dzk3e2bsz"/><path class="pak91mcph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:status-at-hub" {...props}></Icon>
<style>
:global(.dzk3e2bsz) {
  d: path("M11.4 18H2.5V3H18v9.2M2.5 8H18");
}

:global(.pak91mcph) {
  d: path("M8.25 3v8h4V3M17 15h-2v6.5h2m2.5-6.5h2v6.5h-2m-5.25-3.25H22");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gr0js910o"/><path class="uq89zgw5n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shark-warning" {...props}></Icon>
<style>
:global(.gr0js910o) {
  d: path("m12 3l9.5 17h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uq89zgw5n) {
  d: path("M8 16.5c1.5-2 3-5.5 6.5-7v7Z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w-og12zlz"/><path class="r0s-abb2f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:scooter-wheel" {...props}></Icon>
<style>
:global(.r0s-abb2f) {
  d: path("M10.5 16.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM12 15V3.5m-4 0h8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w-og12zlz) {
  d: path("M7 16.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

</style>

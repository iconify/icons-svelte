<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wsr5fgb5v"/><path class="shdwwuy4t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sim-adapter" {...props}></Icon>
<style>
:global(.shdwwuy4t) {
  d: path("M7.5 11h5l3 3v4.5h-8Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wsr5fgb5v) {
  d: path("M4.5 2.5h10l5 5v14h-15Z");
}

</style>

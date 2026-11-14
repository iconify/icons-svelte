<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k782j26ge"/><path class="svjo3qbnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:treasury-liquidity" {...props}></Icon>
<style>
:global(.k782j26ge) {
  d: path("M2.5 6h10a4 4 0 0 1 4 4v1.5h-4v-1a.5.5 0 0 0-.5-.5H2.5M8 6V3M5.5 3h5m.25 14.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.svjo3qbnz) {
  d: path("M13.75 14.75h1.5a3 3 0 0 1 0 6h-1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

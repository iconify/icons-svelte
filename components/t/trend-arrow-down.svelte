<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u0--oacrk"/><path class="v9x-dtmmv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:trend-arrow-down" {...props}></Icon>
<style>
:global(.u0--oacrk) {
  d: path("M3 5c7 0 12 8 17 13");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v9x-dtmmv) {
  d: path("M15 18h5v-5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h4dsnravv"/><path class="pv00t4bca"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:volleyball-spike" {...props}></Icon>
<style>
:global(.h4dsnravv) {
  d: path("M9 15a6 6 0 1 0 12 0a6 6 0 1 0-12 0ZM2.5 6L7 10.5m-1-8L10.5 7");
}

:global(.pv00t4bca) {
  d: path("M15 9c-1.75 2.25-1.75 4.5 0 6m0 0c2-.5 4 .5 5.25 3M15 15c.25 2.25-2.5 3.5-5.25 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

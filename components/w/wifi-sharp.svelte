<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="oema_7bcz"/><path class="rhj7-w4rz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wifi-sharp" {...props}></Icon>
<style>
:global(.oema_7bcz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.82 15.32L12 12.144l3.18 3.176m-9.54-3.18a9 9 0 0 1 12.72 0M2.81 9.31a13 13 0 0 1 18.38 0");
}

:global(.rhj7-w4rz) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18.5h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

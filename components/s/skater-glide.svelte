<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hpoyl6bva"/><path class="dmrkpqeas"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:skater-glide" {...props}></Icon>
<style>
:global(.dmrkpqeas) {
  d: path("M11 21h6a1.5 1.5 0 0 0 1.5-1.5");
}

:global(.hpoyl6bva) {
  d: path("M11.5 4.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2 5.25L13 14.5m-5-2l10.5-3M5 16.5l8-2l1 6.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

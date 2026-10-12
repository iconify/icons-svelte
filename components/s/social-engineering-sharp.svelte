<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="pfv654-ms"/><path class="mzgs10xpk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:social-engineering-sharp" {...props}></Icon>
<style>
:global(.mzgs10xpk) {
  d: path("M2.75 21.25a5.5 5.5 0 0 1 11 0Zm16.5-18.5v9.5a2.25 2.25 0 0 1-4.5 0V11");
}

:global(.pfv654-ms) {
  cx: 8.25px;
  cy: 9px;
  r: 3.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

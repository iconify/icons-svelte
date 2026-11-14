<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q4yjc8mwb"/><path class="ynpc-ybsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:wave-circles" {...props}></Icon>
<style>
:global(.q4yjc8mwb) {
  d: path("M2.5 12a9.5 6 0 1 0 19 0a9.5 6 0 1 0-19 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ynpc-ybsz) {
  d: path("M6.5 12a5.5 3 0 1 0 11 0a5.5 3 0 1 0-11 0Z");
}

</style>

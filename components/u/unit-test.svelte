<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w1a07gb9q"/><path class="ls1zbrb3o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:unit-test" {...props}></Icon>
<style>
:global(.ls1zbrb3o) {
  fill: currentColor;
  d: path("M9.5 13h5v5h-5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w1a07gb9q) {
  d: path("M9 3v6L4 19a1.5 1.5 0 0 0 1.5 2h13a1.5 1.5 0 0 0 1.5-2L15 9V3M7.5 3h9");
}

</style>

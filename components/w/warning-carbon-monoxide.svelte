<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ehs209b4w"/><path class="j3-llgbai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:warning-carbon-monoxide" {...props}></Icon>
<style>
:global(.ehs209b4w) {
  d: path("m12 3l9.5 17.5h-19Z");
}

:global(.j3-llgbai) {
  d: path("M10 17.5a1.75 1.75 0 0 1 0-3.5a2.25 2.25 0 0 1 4 0a1.75 1.75 0 0 1 0 3.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

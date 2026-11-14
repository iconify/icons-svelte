<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y1czhjrxr"/><path class="fsux02bpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:vegan-mark" {...props}></Icon>
<style>
:global(.fsux02bpt) {
  d: path("M12 14c-2 0-3.5-1.25-3.5-3.5c2 0 3.5 1.25 3.5 3.5Zm0-2c2 0 3.5-1.25 3.5-3.5c-2 0-3.5 1.25-3.5 3.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y1czhjrxr) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Zm9.5 5v-7");
}

</style>

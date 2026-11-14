<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ctey_7kfc"/><path class="tps12lbir"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:window-closed" {...props}></Icon>
<style>
:global(.ctey_7kfc) {
  d: path("M3 2.5h18v19H3Zm9 0v19M3 12h18");
}

:global(.tps12lbir) {
  d: path("M14.75 14.75h2.5v4h-2.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

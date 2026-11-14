<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ry2z4cc7s"/><path class="h78w2kbwr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:wifi-calling" {...props}></Icon>
<style>
:global(.h78w2kbwr) {
  d: path("M9.49 5.49a8.5 8.5 0 0 1 12.02 0");
}

:global(.ry2z4cc7s) {
  d: path("M4 7.5h3.25l1 3.5l-1.75 1.5c.75 2 3 4.25 5 5l1.5-1.75l3.5 1V20a1.5 1.5 0 0 1-1.5 1.5C8 21.5 2.5 16 2.5 9A1.5 1.5 0 0 1 4 7.5Zm9.732 2.232a2.5 2.5 0 0 1 3.536 0m-5.657-2.121a5.5 5.5 0 0 1 7.778 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

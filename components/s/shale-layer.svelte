<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k7_ao9bze"/><path class="r0pdnbszv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shale-layer" {...props}></Icon>
<style>
:global(.k7_ao9bze) {
  d: path("M4 4.5h17.5v5H4Zm-1.5 5h17v5h-17Zm1 5h18v5h-18Z");
}

:global(.r0pdnbszv) {
  d: path("m11 4.5l2.5 5l-2 5l2 5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

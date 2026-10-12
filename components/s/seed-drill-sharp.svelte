<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wn4yxxb-l"/><path class="ep1ha2b8w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:seed-drill-sharp" {...props}></Icon>
<style>
:global(.ep1ha2b8w) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 19.75h.01m3.99 0h.01m3.99 0h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.wn4yxxb-l) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 5.75c5.5-2.5 12-2.5 17.5 0L17.5 11.5h-11ZM8 11.5v5m4-5v5m4-5v5");
}

</style>

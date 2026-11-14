<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ghs1vwnec"/><path class="nwnt7_gdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:stdout" {...props}></Icon>
<style>
:global(.ghs1vwnec) {
  d: path("M16.5 14.8V20h-14V4h14v5.2");
}

:global(.nwnt7_gdu) {
  d: path("M5.5 9L8 11.5L5.5 14m5.5-2h10.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

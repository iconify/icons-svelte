<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vrcvc85bf"/><path class="gnvgkd5be"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:smart-meter-hub" {...props}></Icon>
<style>
:global(.gnvgkd5be) {
  d: path("M5.5 12h7v3.5h-7Zm0 6.5H9m6.5-13a3 3 0 0 1 3 3m-3-6a6 6 0 0 1 6 6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vrcvc85bf) {
  d: path("M2.5 9h13v12.5h-13Z");
}

</style>

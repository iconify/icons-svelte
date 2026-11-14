<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gopy5bcxx"/><path class="namg8su1t"/><path class="nzi44zb9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ventilator" {...props}></Icon>
<style>
:global(.gopy5bcxx) {
  d: path("M3 2.5h12v9H3Zm6 9V19m-4.5 0h9");
}

:global(.namg8su1t) {
  d: path("M5.25 7.25H7L8 5l1.5 4.5l1-2.25h2.25M4.5 21h.01m8.99 0h.01M15 4.5c4 0 5.75 2.5 5.75 6v11");
}

:global(.nzi44zb9o) {
  d: path("M15 7.75c1.75 0 2.75 1.25 2.75 2.75v11m0-7.5h3m-3 4h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

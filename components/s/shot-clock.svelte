<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mhuvow97a"/><path class="lu7_x0btz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shot-clock" {...props}></Icon>
<style>
:global(.lu7_x0btz) {
  d: path("M5.5 9H9v6H5.5ZM15 9h3.5v6H15Zm-3 1.5h.01m-.01 3h.01");
}

:global(.mhuvow97a) {
  d: path("M2.5 5.5h19v13h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

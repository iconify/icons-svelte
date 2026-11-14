<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sw24vsbsh"/><path class="fz5z-nxec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:scrubs" {...props}></Icon>
<style>
:global(.fz5z-nxec) {
  d: path("M13 13h3v3.5h-3Z");
}

:global(.sw24vsbsh) {
  d: path("m9 3l3 4l3-4l6 3l-2 4.5l-2-1v11H7v-11l-2 1L3 6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qnssb_suz"/><path class="tknrb0bwh"/><path class="gvmdsibpp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tyre-hard" {...props}></Icon>
<style>
:global(.gvmdsibpp) {
  d: path("M7.25 12a2.75 3.75 0 1 0 5.5 0a2.75 3.75 0 1 0-5.5 0Zm-1.5-3.5a5 7 0 0 0 0 7");
}

:global(.qnssb_suz) {
  d: path("M2.5 12a7.5 9.5 0 1 0 15 0a7.5 9.5 0 1 0-15 0Z");
}

:global(.tknrb0bwh) {
  d: path("M10 2.5h3a7.5 9.5 0 0 1 0 19h-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

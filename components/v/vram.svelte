<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dxc00o28v"/><path class="s-5p85b8l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:vram" {...props}></Icon>
<style>
:global(.dxc00o28v) {
  d: path("M2.5 5.5h19V17h-19ZM6 17v3.5M9.5 17v3.5M13 17v3.5m3.5-3.5v3.5");
}

:global(.s-5p85b8l) {
  d: path("M5.5 8.5H9v5H5.5Zm4.75 0h3.5v5h-3.5Zm4.75 0h3.5v5H15Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

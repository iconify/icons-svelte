<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u5cr2vpme"/><path class="md2nxfbwe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sidebar-toggle" {...props}></Icon>
<style>
:global(.md2nxfbwe) {
  d: path("m15.5 9l-3 3l3 3");
}

:global(.u5cr2vpme) {
  d: path("M2.5 4h19v16h-19Zm6 0v16");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hneliqdkn"/><path class="pxc-9gkqo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sprinkler-controller" {...props}></Icon>
<style>
:global(.hneliqdkn) {
  d: path("M2.5 4h19v16h-19Z");
}

:global(.pxc-9gkqo) {
  d: path("M5.5 7H12v5.5H5.5Zm9.75 2.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM7 16.5h.01m3.49 0h.01m3.49 0h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

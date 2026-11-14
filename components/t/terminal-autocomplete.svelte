<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hneliqdkn"/><path class="dr6uss5xm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:terminal-autocomplete" {...props}></Icon>
<style>
:global(.dr6uss5xm) {
  d: path("M5.5 8.5L8 11l-2.5 2.5m5.25-2.5H13m2.75 0h.01m2.74 0h.01");
}

:global(.hneliqdkn) {
  d: path("M2.5 4h19v16h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

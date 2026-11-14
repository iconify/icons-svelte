<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tr5xbnn7q"/><path class="nwoenz10b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:usb" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nwoenz10b) {
  d: path("M6 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.tr5xbnn7q) {
  d: path("M10 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2-2V4M9.5 6.5l2.5-3l2.5 3M12 14l4.5-2.5v-2m0-3zA1.5 1.5 0 0 1 18 8a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 15 8a1.5 1.5 0 0 1 1.5-1.5M12 12L7.5 9.5v-1");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="e4lze6hle"/><path class="do8xzdz-j"/><path class="i9w8ehb0u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:truck-bell" {...props}></Icon>
<style>
:global(.do8xzdz-j) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 13.75h.01m11.99 0h.01m-6.01 4h.01");
}

:global(.e4lze6hle) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h17M6 3.5V8m6-4.5v4m6-4V8M3.5 10.75a2.5 2.75 0 0 1 5 0v1h-5Zm12 0a2.5 2.75 0 0 1 5 0v1h-5Zm-6 4a2.5 2.75 0 0 1 5 0v1h-5Z");
}

:global(.i9w8ehb0u) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.5V12");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

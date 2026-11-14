<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i0lrkybud"/><path class="p11qepegi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:switch-control" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i0lrkybud) {
  d: path("M7.75 6h8.5a5.25 5.25 0 0 1 5.25 5.25v1.5A5.25 5.25 0 0 1 16.25 18h-8.5a5.25 5.25 0 0 1-5.25-5.25v-1.5A5.25 5.25 0 0 1 7.75 6");
}

:global(.p11qepegi) {
  d: path("M12.5 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>

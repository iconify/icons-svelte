<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ipyya2i8f"/><path class="m8c6ijb9s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shower-tray" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ipyya2i8f) {
  d: path("M5.5 5h13l3 11v3h-19v-3Zm-3 11h19");
}

:global(.m8c6ijb9s) {
  d: path("M9 10.5a3 1.75 0 1 0 6 0a3 1.75 0 1 0-6 0");
}

</style>

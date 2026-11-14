<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nun08ob7f"/><path class="olgu7ac6n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:support-ticket-copy" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nun08ob7f) {
  d: path("M2.5 8.5h16V12a2 2 0 0 0 0 4v3.5h-16V16a2 2 0 0 0 0-4Z");
}

:global(.olgu7ac6n) {
  d: path("M5.5 8.5v-3h16V9a2 2 0 0 0 0 4v3.5h-3");
}

</style>

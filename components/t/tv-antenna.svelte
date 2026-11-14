<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bytyfbbxz"/><path class="stviwsbuh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tv-antenna" {...props}></Icon>
<style>
:global(.bytyfbbxz) {
  d: path("M7.875 9h8.25a4.375 4.375 0 0 1 4.375 4.375v2.75a4.375 4.375 0 0 1-4.375 4.375h-8.25A4.375 4.375 0 0 1 3.5 16.125v-2.75A4.375 4.375 0 0 1 7.875 9M12 9L6.5 3M12 9l5.5-6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.stviwsbuh) {
  d: path("M8.25 12h3.5a1.75 1.75 0 0 1 1.75 1.75v1.5A1.75 1.75 0 0 1 11.75 17h-3.5a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 8.25 12M17 13h.01");
}

</style>

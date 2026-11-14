<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rtdlglrwx"/><path class="n1-nn2b5n"/><path class="g29raibhd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:traffic-light-green" {...props}></Icon>
<style>
:global(.g29raibhd) {
  fill: currentColor;
  d: path("M10.25 16.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n1-nn2b5n) {
  d: path("M10.25 5.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m0 5.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.rtdlglrwx) {
  d: path("M11.625 2h.75a4.375 4.375 0 0 1 4.375 4.375v9.25A4.375 4.375 0 0 1 12.375 20h-.75a4.375 4.375 0 0 1-4.375-4.375v-9.25A4.375 4.375 0 0 1 11.625 2M12 20v2");
}

</style>

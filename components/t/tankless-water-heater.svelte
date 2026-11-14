<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w_gmmjbtb"/><path class="ip64sgv3h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tankless-water-heater" {...props}></Icon>
<style>
:global(.ip64sgv3h) {
  d: path("M12 8.75c0 2.5 4 3.5 4 6.5a4 4 0 0 1-8 0c0-2 1-3 2-3.5c0 1.5.75 2.25 1.5 2.25c0-2.25-.5-3.75.5-5.25Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w_gmmjbtb) {
  d: path("M5.5 5.75h13v16h-13ZM12 2.5v3.25");
}

</style>

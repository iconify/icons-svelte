<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m16qhbb8b"/><path class="wuz3n1w3q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:traffic-cone-duotone-round" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.m16qhbb8b) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10.072 4.629A1 1 0 0 1 11 4h2c.409 0 .777.249.928.629l6 15A.998.998 0 0 1 19 21H5a1 1 0 0 1-.928-1.371Z");
}

:global(.wuz3n1w3q) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m5 20l6-15h2l6 15M3 20h18M9 10h6m-8 5h10");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ga97lpb2d"/><path class="hd5x_f8cb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:threat-event-outline-regular" {...props}></Icon>
<style>
:global(.ga97lpb2d) {
  d: path("M3 5h9v6l-4.5 4.5L3 11Z");
}

:global(.hd5x_f8cb) {
  d: path("m21 7 -4 4h3l-4 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

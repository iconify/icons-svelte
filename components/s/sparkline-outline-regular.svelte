<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hhryeubon"/><path class="oi0elobpe"/><path class="wpfzotbdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sparkline-outline-regular" {...props}></Icon>
<style>
:global(.hhryeubon) {
  d: path("M3 8V3h5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oi0elobpe) {
  d: path("M16 21h5v-5");
}

:global(.wpfzotbdn) {
  d: path("m5 16 4 -4 3 3 4 -4 3 3");
}

</style>

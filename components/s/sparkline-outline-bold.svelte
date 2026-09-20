<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hhryeubon"/><path class="oi0elobpe"/><path class="wpfzotbdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sparkline-outline-bold" {...props}></Icon>
<style>
:global(.hhryeubon) {
  d: path("M3 8V3h5");
}

:global(.oi0elobpe) {
  d: path("M16 21h5v-5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wpfzotbdn) {
  d: path("m5 16 4 -4 3 3 4 -4 3 3");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k3t4pbsco"/><path class="hyn4080vx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:websocket-duocolor-sharp" {...props}></Icon>
<style>
:global(.hyn4080vx) {
  d: path("M3 3v18M21 3v18");
}

:global(.k3t4pbsco) {
  stroke-opacity: 0.4;
  d: path("M7 8h10m-3-3l3 3l-3 3m3 5H7m3-3l-3 3l3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

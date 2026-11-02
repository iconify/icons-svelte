<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="daf2jp9-x"/><path class="vpnf0eemv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:watch-duotone" {...props}></Icon>
<style>
:global(.daf2jp9-x) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 12a5 5 0 1 1 10.001.001A5 5 0 0 1 7 12");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.vpnf0eemv) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 0 0-10 0m2-4V5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v3m-6 8v3a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-3m-3-6v2h2");
}

</style>

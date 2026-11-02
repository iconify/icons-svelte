<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cppd64_2f"/><path class="vrlw9abfp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-sidebar-right-duocolor-sharp" {...props}></Icon>
<style>
:global(.cppd64_2f) {
  stroke-opacity: 0.4;
  d: path("M15 8v12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vrlw9abfp) {
  d: path("M3 8V4h18v16H3zm0 0h18");
}

</style>

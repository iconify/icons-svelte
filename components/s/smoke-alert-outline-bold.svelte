<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uzqto6b0t"/><path class="qmiganh_y"/><path class="gkuwt-n7o"/><path class="hqvb0ld9c"/><path class="bos0j4biy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:smoke-alert-outline-bold" {...props}></Icon>
<style>
:global(.bos0j4biy) {
  d: path("M3 21h18");
}

:global(.gkuwt-n7o) {
  d: path("M9 21a3 3 0 0 1 0 -6");
}

:global(.hqvb0ld9c) {
  d: path("M15 18v-5h5v5Z");
}

:global(.qmiganh_y) {
  d: path("M9 9a3 3 0 0 1 0 6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uzqto6b0t) {
  d: path("M9 9a3 3 0 0 1 0 -6");
}

</style>

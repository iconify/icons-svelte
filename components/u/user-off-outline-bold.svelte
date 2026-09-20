<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ppbx_abyw"/><path class="v-u0ijc7h"/><path class="h7leix15f"/><path class="kx-wgwbez"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:user-off-outline-bold" {...props}></Icon>
<style>
:global(.h7leix15f) {
  d: path("m15 9 6 6");
}

:global(.kx-wgwbez) {
  d: path("m21 9 -6 6");
}

:global(.ppbx_abyw) {
  d: path("M6 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v-u0ijc7h) {
  d: path("M3 21a6 6 0 0 1 12 0");
}

</style>

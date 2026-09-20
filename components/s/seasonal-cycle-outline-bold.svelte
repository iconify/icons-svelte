<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h06k0cc0f"/><path class="oh3qc3kah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:seasonal-cycle-outline-bold" {...props}></Icon>
<style>
:global(.h06k0cc0f) {
  d: path("M3 12a4 4 0 0 1 8 0");
}

:global(.oh3qc3kah) {
  d: path("M19 12a4 4 0 0 1 -8 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

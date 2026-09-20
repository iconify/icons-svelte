<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bwswnubai"/><path class="ic00xab8f"/><path class="tdux9oy4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:treasure-chest-outline-bold" {...props}></Icon>
<style>
:global(.bwswnubai) {
  d: path("M4 12v9h16v-9Z");
}

:global(.ic00xab8f) {
  d: path("M4 12a8 8 0 0 1 16 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tdux9oy4s) {
  d: path("M10 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

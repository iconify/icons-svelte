<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g-kdil3dv"/><path class="rencte-ct"/><path class="bwswnubai"/><path class="ic00xab8f"/><path class="tdux9oy4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:treasure-chest-duotone-regular" {...props}></Icon>
<style>
:global(.bwswnubai) {
  d: path("M4 12v9h16v-9Z");
}

:global(.g-kdil3dv) {
  fill: currentColor;
  d: path("M4 12v9h16v-9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ic00xab8f) {
  d: path("M4 12a8 8 0 0 1 16 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rencte-ct) {
  fill: currentColor;
  d: path("M10 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tdux9oy4s) {
  d: path("M10 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ut22q-b2l"/><path class="qx4fzbhlz"/><path class="ah0cuqn_g"/><path class="q534om6ef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sd-card-outline-regular" {...props}></Icon>
<style>
:global(.ah0cuqn_g) {
  d: path("M11 5v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q534om6ef) {
  d: path("M14 8v4");
}

:global(.qx4fzbhlz) {
  d: path("M8 5v4");
}

:global(.ut22q-b2l) {
  d: path("M4 2h11l5 5v15H4Z");
}

</style>

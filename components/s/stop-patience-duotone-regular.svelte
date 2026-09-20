<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pba3vx25x"/><path class="pesxdybze"/><path class="qxju3_sgm"/><path class="eky6twzzr"/><path class="trk8friyx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stop-patience-duotone-regular" {...props}></Icon>
<style>
:global(.eky6twzzr) {
  d: path("M16.5 9.5V12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pba3vx25x) {
  fill: currentColor;
  d: path("M12.5 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pesxdybze) {
  d: path("M3 12h7");
}

:global(.qxju3_sgm) {
  d: path("M12.5 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.trk8friyx) {
  d: path("M16.5 12H19");
}

</style>

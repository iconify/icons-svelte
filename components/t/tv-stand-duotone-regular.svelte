<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tpztwbcbc"/><path class="yx7yyttaj"/><path class="olbeg_6gm"/><path class="m6nkjhiin"/><path class="dfugeobed"/><path class="vhf3_kexp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tv-stand-duotone-regular" {...props}></Icon>
<style>
:global(.dfugeobed) {
  d: path("M3 16h18v5H3Z");
}

:global(.m6nkjhiin) {
  d: path("M12 13v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.olbeg_6gm) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.tpztwbcbc) {
  fill: currentColor;
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vhf3_kexp) {
  d: path("M12 16v5");
}

:global(.yx7yyttaj) {
  fill: currentColor;
  d: path("M3 16h18v5H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

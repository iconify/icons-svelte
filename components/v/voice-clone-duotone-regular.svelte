<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nbz-o_0uq"/><path class="buii30epg"/><path class="f4omdhbvv"/><path class="mqjjm8bwi"/><path class="g8q62k13p"/><path class="n49oq7__n"/><path class="kt4vswbcx"/><path class="u9ungwb-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:voice-clone-duotone-regular" {...props}></Icon>
<style>
:global(.buii30epg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3.76 16.24a6 6 0 0 1 0 -8.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f4omdhbvv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18.12 9.88a3 3 0 0 1 0 4.24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g8q62k13p) {
  d: path("M5.88 14.12a3 3 0 0 1 0 -4.24");
}

:global(.kt4vswbcx) {
  d: path("M18.12 9.88a3 3 0 0 1 0 4.24");
}

:global(.mqjjm8bwi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20.24 7.76a6 6 0 0 1 0 8.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n49oq7__n) {
  d: path("M3.76 16.24a6 6 0 0 1 0 -8.5");
}

:global(.nbz-o_0uq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.88 14.12a3 3 0 0 1 0 -4.24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u9ungwb-f) {
  d: path("M20.24 7.76a6 6 0 0 1 0 8.5");
}

</style>

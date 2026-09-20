<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sgps_g3sy"/><path class="sutfpibts"/><path class="mprhlt90i"/><path class="yb9iu4bmw"/><path class="ffs26fbkv"/><path class="wneoubc6n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:video-game-duotone-regular" {...props}></Icon>
<style>
:global(.ffs26fbkv) {
  d: path("M12 17v4");
}

:global(.mprhlt90i) {
  d: path("M3 4v13h18V4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sgps_g3sy) {
  fill: currentColor;
  d: path("M3 4v13h18V4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.sutfpibts) {
  fill: currentColor;
  d: path("M9 8h6v5H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wneoubc6n) {
  d: path("M7 21h10");
}

:global(.yb9iu4bmw) {
  d: path("M9 8h6v5H9Z");
}

</style>

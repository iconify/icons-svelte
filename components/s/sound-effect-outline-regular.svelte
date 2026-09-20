<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v_bqwbcfx"/><path class="kat3by1wu"/><path class="izng5ebil"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sound-effect-outline-regular" {...props}></Icon>
<style>
:global(.izng5ebil) {
  d: path("M18.24 8.76a6 6 0 0 1 0 8.5");
}

:global(.kat3by1wu) {
  d: path("M16.12 10.88a3 3 0 0 1 0 4.24");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v_bqwbcfx) {
  d: path("m11 5 -5 5h4l-5 5");
}

</style>

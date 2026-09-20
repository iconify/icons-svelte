<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wp32b-b4l"/><path class="kl15gcoth"/><path class="wspsoebse"/><path class="v_bqwbcfx"/><path class="kat3by1wu"/><path class="izng5ebil"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sound-effect-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.izng5ebil) {
  d: path("M18.24 8.76a6 6 0 0 1 0 8.5");
}

:global(.kat3by1wu) {
  d: path("M16.12 10.88a3 3 0 0 1 0 4.24");
}

:global(.kl15gcoth) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16.12 10.88a3 3 0 0 1 0 4.24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v_bqwbcfx) {
  d: path("m11 5 -5 5h4l-5 5");
}

:global(.wp32b-b4l) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m11 5 -5 5h4l-5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wspsoebse) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18.24 8.76a6 6 0 0 1 0 8.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kr5if0b2e"/><path class="pr270rb6e"/><path class="ppbx_abyw"/><path class="v-u0ijc7h"/><path class="d_xtg74gy"/><path class="iu_19hbrz"/><path class="bpyxkfv4l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:user-key-duotone-thin" {...props}></Icon>
<style>
:global(.bpyxkfv4l) {
  d: path("M17 14.5h2.5");
}

:global(.d_xtg74gy) {
  d: path("M15 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iu_19hbrz) {
  d: path("M17 12v4.5");
}

:global(.kr5if0b2e) {
  fill: currentColor;
  d: path("M6 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ppbx_abyw) {
  d: path("M6 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.pr270rb6e) {
  fill: currentColor;
  d: path("M15 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.v-u0ijc7h) {
  d: path("M3 21a6 6 0 0 1 12 0");
}

</style>

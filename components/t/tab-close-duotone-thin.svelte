<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lid4b7x8u"/><path class="ior14cbcm"/><path class="pu39tea_e"/><path class="zb7x15uln"/><path class="oscmqi7_r"/><path class="z9ittvbis"/><path class="oh3t_sdfd"/><path class="b4nrz0b6r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tab-close-duotone-thin" {...props}></Icon>
<style>
:global(.b4nrz0b6r) {
  d: path("m20.5 10.5 -5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ior14cbcm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lid4b7x8u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19V9l2 -2h6l2 2v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oh3t_sdfd) {
  d: path("m15.5 10.5 5 5");
}

:global(.oscmqi7_r) {
  d: path("M2 19V9l2 -2h6l2 2v10");
}

:global(.pu39tea_e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15.5 10.5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

:global(.zb7x15uln) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m20.5 10.5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

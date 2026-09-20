<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lid4b7x8u"/><path class="ior14cbcm"/><path class="mxollbc1y"/><path class="yeq6ekb5h"/><path class="oscmqi7_r"/><path class="z9ittvbis"/><path class="qvtmo6b3b"/><path class="a46bghb1i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tab-new-duotone-thin" {...props}></Icon>
<style>
:global(.a46bghb1i) {
  d: path("M18 10v6");
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

:global(.mxollbc1y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oscmqi7_r) {
  d: path("M2 19V9l2 -2h6l2 2v10");
}

:global(.qvtmo6b3b) {
  d: path("M15 13h6");
}

:global(.yeq6ekb5h) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hma_3gb4g"/><path class="jf8si_b8r"/><path class="onmmgdbjv"/><path class="bos0j4biy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:writing-duotone-thin" {...props}></Icon>
<style>
:global(.bos0j4biy) {
  d: path("M3 21h18");
}

:global(.hma_3gb4g) {
  fill: currentColor;
  d: path("M6 13 16 3l3 3L9 16Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jf8si_b8r) {
  d: path("M6 13 16 3l3 3L9 16Z");
}

:global(.onmmgdbjv) {
  d: path("m6 13 -2 2v3h3l2 -2");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="t94gi6bhh"/><path class="wtr271uqu"/><path class="t-3s33n5f"/><path class="tw7777n4m"/><path class="xgrfb-bqu"/><path class="r4xjkv11f"/><path class="n-7t0yb1r"/><path class="ukjt4fb6s"/><path class="yvi-t83_e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:top-k-duotone-thin" {...props}></Icon>
<style>
:global(.earhjk-cy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n-7t0yb1r) {
  d: path("M3 13h18");
}

:global(.r4xjkv11f) {
  d: path("M3 10h15");
}

:global(.t-3s33n5f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t94gi6bhh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 10h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tw7777n4m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ukjt4fb6s) {
  d: path("M3 17h12");
}

:global(.wtr271uqu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 13h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.yvi-t83_e) {
  d: path("M3 21h9");
}

</style>

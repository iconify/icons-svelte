<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="c58ve3zov"/><path class="oiqg4cbka"/><path class="k6nj2fbya"/><path class="x50q_4bdr"/><path class="vwjk1ok-c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:transcribe-live-duotone-thin" {...props}></Icon>
<style>
:global(.c58ve3zov) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 10h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ck7sgubpk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.oiqg4cbka) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h4l2.5 -2.5L12 17l2.5 -2.5L17 17h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vwjk1ok-c) {
  d: path("M3 17h4l2.5 -2.5L12 17l2.5 -2.5L17 17h4");
}

:global(.x50q_4bdr) {
  d: path("M3 10h18");
}

</style>

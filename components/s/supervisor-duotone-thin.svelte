<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nwjk04b5m"/><path class="r1_8apbkr"/><path class="rsdr_lcda"/><path class="qztqcduuj"/><path class="nj458u4vq"/><path class="d-tnphbnb"/><path class="mq1k2k45m"/><path class="i8t3_pbsa"/><path class="cuxt49b2j"/><path class="vs9lv0b4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:supervisor-duotone-thin" {...props}></Icon>
<style>
:global(.cuxt49b2j) {
  d: path("m9.5 10.5 -2 2");
}

:global(.d-tnphbnb) {
  d: path("M13.27 5.28a3 3 0 1 1 -2.54 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i8t3_pbsa) {
  d: path("M20.27 12.28a3 3 0 1 1 -2.54 0");
}

:global(.mq1k2k45m) {
  d: path("M6.27 12.28a3 3 0 1 1 -2.54 0");
}

:global(.nj458u4vq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14.5 10.5 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nwjk04b5m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.27 5.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qztqcduuj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9.5 10.5 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r1_8apbkr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6.27 12.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rsdr_lcda) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20.27 12.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vs9lv0b4s) {
  d: path("m14.5 10.5 2 2");
}

</style>

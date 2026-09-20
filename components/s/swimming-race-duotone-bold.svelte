<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o0u5m7z1w"/><path class="off21u63l"/><path class="lqh1gn8dx"/><path class="m7em9hbgd"/><path class="g_eatebwd"/><path class="prj9u5frn"/><path class="neof5acyb"/><path class="jg5yyubai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:swimming-race-duotone-bold" {...props}></Icon>
<style>
:global(.g_eatebwd) {
  d: path("M5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.jg5yyubai) {
  d: path("M3 16c3 -2 6 2 9 0s6 2 9 0");
}

:global(.lqh1gn8dx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 10 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m7em9hbgd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16c3 -2 6 2 9 0s6 2 9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.neof5acyb) {
  d: path("m14 10 4 -4");
}

:global(.o0u5m7z1w) {
  fill: currentColor;
  d: path("M5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.off21u63l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 10h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.prj9u5frn) {
  d: path("M9 10h5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

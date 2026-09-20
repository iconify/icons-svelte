<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vrytpeb1k"/><path class="agv117egc"/><path class="in03m4f8p"/><path class="mn7zxg3cy"/><path class="dx_oex_yx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:video-lesson-duotone-bold" {...props}></Icon>
<style>
:global(.agv117egc) {
  d: path("M2 11a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.dx_oex_yx) {
  d: path("m15 9 4 -4");
}

:global(.in03m4f8p) {
  d: path("m2 9 4 -4h16v4");
}

:global(.mn7zxg3cy) {
  d: path("m9 9 4 -4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vrytpeb1k) {
  fill: currentColor;
  d: path("M2 11a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

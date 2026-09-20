<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p3f03tbmh"/><path class="acja6ya7a"/><path class="j9kdj-bfk"/><path class="zoz5ar7wf"/><path class="ke4ug0b-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:student-duotone-bold" {...props}></Icon>
<style>
:global(.acja6ya7a) {
  fill: currentColor;
  d: path("M9 14a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.j9kdj-bfk) {
  d: path("m4 7 3 -3h10l3 3 -3 3H7Z");
}

:global(.ke4ug0b-p) {
  d: path("M7.5 21a4.5 4.5 0 0 1 9 0");
}

:global(.p3f03tbmh) {
  fill: currentColor;
  d: path("m4 7 3 -3h10l3 3 -3 3H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zoz5ar7wf) {
  d: path("M9 14a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>

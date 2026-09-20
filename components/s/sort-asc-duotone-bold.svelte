<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e63e9dbag"/><path class="kaukupb-u"/><path class="km2_vvbqp"/><path class="mt0duqbnk"/><path class="xlekzhbnl"/><path class="o8od38cnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sort-asc-duotone-bold" {...props}></Icon>
<style>
:global(.e63e9dbag) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kaukupb-u) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.km2_vvbqp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mt0duqbnk) {
  d: path("M4 6h6");
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xlekzhbnl) {
  d: path("M4 12h11");
}

</style>

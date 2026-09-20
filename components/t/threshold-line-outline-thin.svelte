<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="e_6o-gbms"/><path class="a5uqb5btg"/><path class="qn21uclav"/><path class="mcdduacou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:threshold-line-outline-thin" {...props}></Icon>
<style>
:global(.a5uqb5btg) {
  d: path("M9 14v4");
}

:global(.e_6o-gbms) {
  d: path("M6 10h13");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mcdduacou) {
  d: path("M17 7v11");
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.qn21uclav) {
  d: path("M13 12v6");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

</style>

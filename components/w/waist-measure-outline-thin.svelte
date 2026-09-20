<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kamdbib6v"/><path class="pmuiqo95v"/><path class="kt4_ogrrr"/><path class="hgjyjobhk"/><path class="gvpticbjc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:waist-measure-outline-thin" {...props}></Icon>
<style>
:global(.gvpticbjc) {
  d: path("M18 7v4");
}

:global(.hgjyjobhk) {
  d: path("M12 7v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kamdbib6v) {
  d: path("M2 7h20");
}

:global(.kt4_ogrrr) {
  d: path("M6 7v4");
}

:global(.pmuiqo95v) {
  d: path("M2 17h20");
}

</style>

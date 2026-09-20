<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kamdbib6v"/><path class="pmuiqo95v"/><path class="kt4_ogrrr"/><path class="hgjyjobhk"/><path class="gvpticbjc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:waist-measure-outline-regular" {...props}></Icon>
<style>
:global(.gvpticbjc) {
  d: path("M18 7v4");
}

:global(.hgjyjobhk) {
  d: path("M12 7v4");
}

:global(.kamdbib6v) {
  d: path("M2 7h20");
}

:global(.kt4_ogrrr) {
  d: path("M6 7v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pmuiqo95v) {
  d: path("M2 17h20");
}

</style>

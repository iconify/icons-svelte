<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lrgwget7i"/><path class="rvot348of"/><path class="entdgs0no"/><path class="q30lbsbyl"/><path class="f8gsx7b5s"/><path class="vn9zmkbyj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shade-tint-duotone-regular" {...props}></Icon>
<style>
:global(.entdgs0no) {
  d: path("M3 5h18v6H3Z");
}

:global(.f8gsx7b5s) {
  d: path("M6 8h12");
}

:global(.lrgwget7i) {
  fill: currentColor;
  d: path("M3 5h18v6H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q30lbsbyl) {
  d: path("M3 14h18v6H3Z");
}

:global(.rvot348of) {
  fill: currentColor;
  d: path("M3 14h18v6H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vn9zmkbyj) {
  d: path("M12 17h6");
}

</style>

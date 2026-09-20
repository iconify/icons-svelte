<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="apfmjihmc"/><path class="hcbxlsosl"/><path class="pdlat6brq"/><path class="z4g4wjbvf"/><path class="spjil5bml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tap-water-duotone-bold" {...props}></Icon>
<style>
:global(.apfmjihmc) {
  fill: currentColor;
  d: path("m16 13 3 3a3 3 0 0 1 -6 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hcbxlsosl) {
  d: path("M4 6h8v6h4");
}

:global(.pdlat6brq) {
  d: path("M9 3v3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.spjil5bml) {
  d: path("m16 13 3 3a3 3 0 0 1 -6 0Z");
}

:global(.z4g4wjbvf) {
  d: path("M6 3h6");
}

</style>

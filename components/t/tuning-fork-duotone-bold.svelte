<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="i-83xabxj"/><path class="koxc2rbcm"/><path class="vmp8eebwz"/><path class="g6bypobmt"/><path class="ftej-1ggr"/><path class="p_xsqcbww"/><path class="o3x_gzblq"/><path class="ffs26fbkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tuning-fork-duotone-bold" {...props}></Icon>
<style>
:global(.ffs26fbkv) {
  d: path("M12 17v4");
}

:global(.ftej-1ggr) {
  d: path("M8 3v10");
}

:global(.g6bypobmt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 17v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i-83xabxj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 3v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.koxc2rbcm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 3v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o3x_gzblq) {
  d: path("m8 13 4 4 4 -4");
}

:global(.p_xsqcbww) {
  d: path("M16 3v10");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vmp8eebwz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 13 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lkf70kb4f"/><path class="jbblsqbig"/><path class="z07djwbph"/><path class="m6ifjboxi"/><path class="ftej-1ggr"/><path class="p_xsqcbww"/><path class="o3x_gzblq"/><path class="ffs26fbkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tuning-fork-duotone-regular" {...props}></Icon>
<style>
:global(.ffs26fbkv) {
  d: path("M12 17v4");
}

:global(.ftej-1ggr) {
  d: path("M8 3v10");
}

:global(.jbblsqbig) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 3v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lkf70kb4f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 3v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m6ifjboxi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 17v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o3x_gzblq) {
  d: path("m8 13 4 4 4 -4");
}

:global(.p_xsqcbww) {
  d: path("M16 3v10");
}

:global(.z07djwbph) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 13 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ow9nvovdw"/><path class="qzpkx5nxr"/><path class="g3zhfu7cw"/><path class="zp2a9sb8n"/><path class="ymi7xlb0o"/><path class="b7nacdcee"/><path class="p2x4fkb_u"/><path class="pt-3kkb2k"/><path class="vd0jm7r_j"/><path class="p0o5ir5ue"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sparse-search-duotone-regular" {...props}></Icon>
<style>
:global(.b7nacdcee) {
  d: path("M3 6h6");
}

:global(.g3zhfu7cw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 11h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ow9nvovdw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p0o5ir5ue) {
  d: path("M15 16h6");
}

:global(.p2x4fkb_u) {
  d: path("M15 6h6");
}

:global(.pt-3kkb2k) {
  d: path("M9 11h6");
}

:global(.qzpkx5nxr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vd0jm7r_j) {
  d: path("M3 16h6");
}

:global(.ymi7xlb0o) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zp2a9sb8n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

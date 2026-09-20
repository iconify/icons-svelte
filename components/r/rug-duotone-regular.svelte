<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="arao4zbuf"/><path class="z_pwnvbbd"/><path class="o-vpc-waj"/><path class="yq_iz_bvt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rug-duotone-regular" {...props}></Icon>
<style>
:global(.arao4zbuf) {
  fill: currentColor;
  d: path("M3 12a9 4.5 0 1 1 18 0 9 4.5 0 1 1 -18 0");
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

:global(.o-vpc-waj) {
  d: path("M3 12a9 4.5 0 1 1 18 0 9 4.5 0 1 1 -18 0");
}

:global(.yq_iz_bvt) {
  d: path("M6 12a6 3 0 1 1 12 0 6 3 0 1 1 -12 0");
}

:global(.z_pwnvbbd) {
  fill: currentColor;
  d: path("M6 12a6 3 0 1 1 12 0 6 3 0 1 1 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

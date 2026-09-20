<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rhgd1j5xm"/><path class="urilmibxp"/><path class="ggik2wgcv"/><path class="iwjts2bwl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:souvenir-outline-regular" {...props}></Icon>
<style>
:global(.ggik2wgcv) {
  d: path("M9 9V5h6v4");
}

:global(.iwjts2bwl) {
  d: path("m12 15 2 2 -2 2 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rhgd1j5xm) {
  d: path("M4 11a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.urilmibxp) {
  d: path("M4 13h16");
}

</style>

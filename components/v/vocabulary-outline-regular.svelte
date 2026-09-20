<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zrwkhybyf"/><path class="hg1j_lbce"/><path class="il4f-53br"/><path class="uv-0dacjj"/><path class="mf-afdped"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vocabulary-outline-regular" {...props}></Icon>
<style>
:global(.hg1j_lbce) {
  d: path("M7 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.il4f-53br) {
  d: path("M15 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mf-afdped) {
  d: path("M15 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uv-0dacjj) {
  d: path("M7 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zrwkhybyf) {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>

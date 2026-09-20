<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zrwkhybyf"/><path class="hg1j_lbce"/><path class="il4f-53br"/><path class="uv-0dacjj"/><path class="mf-afdped"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vocabulary-outline-thin" {...props}></Icon>
<style>
:global(.hg1j_lbce) {
  d: path("M7 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.il4f-53br) {
  d: path("M15 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mf-afdped) {
  d: path("M15 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.uv-0dacjj) {
  d: path("M7 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zrwkhybyf) {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>

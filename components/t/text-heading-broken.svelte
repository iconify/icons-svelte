<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q11q8pbau"/><path class="a9_g1_bko"/><path class="btex5sb2a"/><path class="h3s_qfbzc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-heading-broken" {...props}></Icon>
<style>
:global(.a9_g1_bko) {
  d: path("M5 18V22");
}

:global(.btex5sb2a) {
  d: path("M19 2V22");
}

:global(.h3s_qfbzc) {
  d: path("M5 12H19");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q11q8pbau) {
  d: path("M5 2V14");
}

</style>

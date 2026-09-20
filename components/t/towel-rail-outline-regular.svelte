<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k6nj2fbya"/><path class="kif6g-eik"/><path class="enh0e8a0v"/><path class="hczrfxb9f"/><path class="qtxvlht3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:towel-rail-outline-regular" {...props}></Icon>
<style>
:global(.enh0e8a0v) {
  d: path("M21 5v3");
}

:global(.hczrfxb9f) {
  d: path("M8 5v15h8V5");
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.kif6g-eik) {
  d: path("M3 5v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qtxvlht3c) {
  d: path("M8 17h8");
}

</style>

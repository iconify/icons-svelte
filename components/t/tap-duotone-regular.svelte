<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n3wtsvdya"/><path class="ha05_q27d"/><path class="w2b54lbpr"/><path class="xb-kv0a1i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tap-duotone-regular" {...props}></Icon>
<style>
:global(.ha05_q27d) {
  d: path("M5 4v6h11v3");
}

:global(.n3wtsvdya) {
  fill: currentColor;
  d: path("m16 15 2.5 2.5a3 3 0 1 1 -5 0Z");
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

:global(.w2b54lbpr) {
  d: path("M3 4h5");
}

:global(.xb-kv0a1i) {
  d: path("m16 15 2.5 2.5a3 3 0 1 1 -5 0Z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xz6r43u8w"/><path class="fo-cubb-j"/><path class="mcuujfb5l"/><path class="phi1ncbih"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sanitiser-outline-regular" {...props}></Icon>
<style>
:global(.fo-cubb-j) {
  d: path("M11 10V4h5");
}

:global(.mcuujfb5l) {
  d: path("M16 4v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.phi1ncbih) {
  d: path("M6 15h10");
}

:global(.xz6r43u8w) {
  d: path("M6 21V10h10v11Z");
}

</style>

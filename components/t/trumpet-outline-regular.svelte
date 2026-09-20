<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="akyaa-boy"/><path class="nuk2gwb4b"/><path class="gstzuxb9r"/><path class="ldq326b0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trumpet-outline-regular" {...props}></Icon>
<style>
:global(.akyaa-boy) {
  d: path("M13 11H2v4h11");
}

:global(.gstzuxb9r) {
  d: path("M5 7v4");
}

:global(.ldq326b0y) {
  d: path("M9 7v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nuk2gwb4b) {
  d: path("m13 9 6 -6v18l-6 -6Z");
}

</style>

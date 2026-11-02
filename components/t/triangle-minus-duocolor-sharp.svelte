<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qfg574k9n"/><path class="byr2wcn0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:triangle-minus-duocolor-sharp" {...props}></Icon>
<style>
:global(.byr2wcn0d) {
  d: path("m12 2l10 18H2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qfg574k9n) {
  stroke-opacity: 0.4;
  d: path("M10 14h4");
}

</style>

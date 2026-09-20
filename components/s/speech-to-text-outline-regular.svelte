<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d90oeycoz"/><path class="cnwhnbbmh"/><path class="ub1mcfbjy"/><path class="v90yymbhv"/><path class="yy6mapbcz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:speech-to-text-outline-regular" {...props}></Icon>
<style>
:global(.cnwhnbbmh) {
  d: path("M11 13a4 4 0 0 1 -8 0");
}

:global(.d90oeycoz) {
  d: path("M4 7a3 3 0 0 1 3 -3 3 3 0 0 1 3 3v4a3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ub1mcfbjy) {
  d: path("M14 9h7");
}

:global(.v90yymbhv) {
  d: path("M14 14h7");
}

:global(.yy6mapbcz) {
  d: path("M14 19h4");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="asd1gsbjs"/><path class="rn124nbga"/><path class="wh01pcbbr"/><path class="jcxg2bbvb"/><path class="fyyr_6-1m"/><path class="ue-dwjbmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:splitter-duotone-regular" {...props}></Icon>
<style>
:global(.asd1gsbjs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fyyr_6-1m) {
  d: path("m10 12 4 -4h7");
}

:global(.jcxg2bbvb) {
  d: path("M2 12h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rn124nbga) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 12 4 -4h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ue-dwjbmw) {
  d: path("m10 12 4 4h7");
}

:global(.wh01pcbbr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 12 4 4h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

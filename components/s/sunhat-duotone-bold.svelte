<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ycftzzhuq"/><path class="hootrpbsy"/><path class="keeez031w"/><path class="l8dn9jbyp"/><path class="y006j0y9x"/><path class="olqfcgidt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sunhat-duotone-bold" {...props}></Icon>
<style>
:global(.hootrpbsy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 15a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.keeez031w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l8dn9jbyp) {
  d: path("M2 15h20");
}

:global(.olqfcgidt) {
  d: path("M6 19h12");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.y006j0y9x) {
  d: path("M6 15a6 6 0 0 1 12 0");
}

:global(.ycftzzhuq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 15h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGDimLcemV" class="tavp01vsf"/></defs><use href="#SVGDimLcemV" class="c-zrgpb5l"/><use href="#SVGDimLcemV" class="c-zrgpb5l"/><circle class="x3_wer0dr"/><path class="rnn9ijbsn"/><path class="m8u510jcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:unified-remote" {...props}></Icon>
<style>
:global(.c-zrgpb5l) {
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.m8u510jcm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.713 42.5A19.516 19.516 0 0 0 5.5 18.287");
}

:global(.rnn9ijbsn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.392 5.835A31.527 31.527 0 0 1 42.5 37a32 32 0 0 1-.335 4.608");
}

:global(.tavp01vsf) {
  fill: none;
  stroke: currentColor;
  d: path("M11 5.5A31.5 31.5 0 0 1 42.5 37");
}

:global(.x3_wer0dr) {
  cx: 11px;
  cy: 37px;
  r: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

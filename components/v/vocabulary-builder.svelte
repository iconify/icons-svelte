<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="f8i38xf_e"/><path class="tpwdo92fb"/><circle class="j8-k2_lgg"/><path class="wcc5habbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:vocabulary-builder" {...props}></Icon>
<style>
:global(.f8i38xf_e) {
  width: 34.789px;
  height: 7.053px;
  x: 6.605px;
  y: 35.447px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.395px;
  ry: 2.395px;
}

:global(.j8-k2_lgg) {
  cx: 24px;
  cy: 18.737px;
  r: 13.237px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tpwdo92fb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.816 35.447V42.5");
}

:global(.wcc5habbr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.467 18.737l6.18 6.18l10.886-10.886");
}

</style>

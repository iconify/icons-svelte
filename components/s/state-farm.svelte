<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="ovlc1cbnd"/><ellipse class="u7m-vfbib"/><ellipse class="tpbfp3bon"/><ellipse class="pf72jxbij"/><ellipse class="w8ldgdbrv"/><ellipse class="dg096uvwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:state-farm" {...props}></Icon>
<style>
:global(.dg096uvwi) {
  cx: 33.75px;
  cy: 29.701px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9.75px;
  ry: 6.548px;
}

:global(.ovlc1cbnd) {
  cx: 14.25px;
  cy: 29.686px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.06px;
  ry: 4.035px;
}

:global(.pf72jxbij) {
  cx: 24px;
  cy: 18.299px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9.75px;
  ry: 6.548px;
}

:global(.tpbfp3bon) {
  cx: 24px;
  cy: 18.352px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.06px;
  ry: 4.035px;
}

:global(.u7m-vfbib) {
  cx: 14.25px;
  cy: 29.633px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9.75px;
  ry: 6.548px;
}

:global(.w8ldgdbrv) {
  cx: 33.75px;
  cy: 29.754px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.06px;
  ry: 4.035px;
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="gaca01bsz"/><rect class="jvnmb1bnj"/><rect class="ll0ta6bui"/><rect class="xn1z65bsw"/><rect class="kuq85-djq"/><rect class="rqy01xcpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sputter" {...props}></Icon>
<style>
:global(.gaca01bsz) {
  width: 9.867px;
  height: 9.867px;
  x: 5.001px;
  y: 32.309px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.jvnmb1bnj) {
  width: 9.867px;
  height: 9.867px;
  x: 18.568px;
  y: 32.309px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.kuq85-djq) {
  width: 9.867px;
  height: 9.867px;
  x: 18.568px;
  y: 5.176px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.ll0ta6bui) {
  width: 9.867px;
  height: 9.867px;
  x: 5.001px;
  y: 18.742px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.rqy01xcpg) {
  width: 9.867px;
  height: 9.867px;
  x: 32.134px;
  y: 5.176px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.xn1z65bsw) {
  width: 9.867px;
  height: 9.867px;
  x: 32.134px;
  y: 18.742px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

</style>

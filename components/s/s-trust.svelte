<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="clyy6mbyw"/><rect class="qgijx9buz"/><path class="k9b0mvprd"/><circle class="uhp41y_jr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:s-trust" {...props}></Icon>
<style>
:global(.clyy6mbyw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c1.693 0 15.274-7.782 15.274-16.966V6.504C35.267 6.503 24 4.5 24 4.5S12.723 6.503 8.727 6.503v20.03C8.727 35.719 22.307 43.5 24 43.5");
}

:global(.k9b0mvprd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.845 22.339h14.817m-19.324 5.573h14.817");
}

:global(.qgijx9buz) {
  width: 19.325px;
  height: 16.718px;
  x: 14.338px;
  y: 16.767px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.746px;
}

:global(.uhp41y_jr) {
  cx: 23.987px;
  cy: 11.656px;
  r: 3.21px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

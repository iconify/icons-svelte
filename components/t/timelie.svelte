<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="monwjgsfi"/><path class="gh_xr2bws"/><circle class="dey00kd_q"/><circle class="hg2r4ybgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:timelie" {...props}></Icon>
<style>
:global(.dey00kd_q) {
  cx: 20.506px;
  cy: 20px;
  r: 0.75px;
  fill: currentColor;
}

:global(.gh_xr2bws) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.506 14v20l17-10zm0 0l8.87 14.783m-.001-9.566L14.505 34m17.001-10h-17");
}

:global(.hg2r4ybgt) {
  cx: 20.506px;
  cy: 28px;
  r: 0.75px;
  fill: currentColor;
}

:global(.monwjgsfi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.506 6v36l30.988-18z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wb9edgbms"/><circle class="tav-gubox"/><circle class="awdcneboh"/><path class="mx7lyqzxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sbi-securities-stock" {...props}></Icon>
<style>
:global(.awdcneboh) {
  cx: 24px;
  cy: 30.113px;
  r: 3.258px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.mx7lyqzxi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 33.371V43.5");
}

:global(.tav-gubox) {
  cx: 24px;
  cy: 30.113px;
  r: 13.387px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wb9edgbms) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.342 4.5v9.683m-5.369-4.842a2.42 2.42 0 0 1 0 4.842H23.98V4.5h3.994a2.42 2.42 0 0 1 0 4.841m-.001 0h-3.994m-9.129 3.781c.593.773 1.338 1.06 2.374 1.06h1.433a2.416 2.416 0 0 0 2.416-2.415v-.01a2.416 2.416 0 0 0-2.416-2.416h-1.581a2.42 2.42 0 0 1-2.418-2.418h0A2.423 2.423 0 0 1 17.08 4.5h1.426c1.036 0 1.78.288 2.374 1.06");
}

</style>

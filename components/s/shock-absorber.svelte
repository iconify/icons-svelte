<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="t88z8mbby"/><path class="odcry9b4p"/><rect class="aatz2tb9q"/><path class="sjnr11qhx"/><circle class="j1-unv-pk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:shock-absorber" {...props}></Icon>
<style>
:global(.aatz2tb9q) {
  width: 7px;
  height: 6.5px;
  x: 8.5px;
  y: 9px;
  rx: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j1-unv-pk) {
  cx: 12px;
  cy: 19.5px;
  r: 1.75px;
}

:global(.odcry9b4p) {
  d: path("M12 6.25V9");
}

:global(.sjnr11qhx) {
  d: path("M8.5 12.25h7M12 15.5v2.25");
}

:global(.t88z8mbby) {
  cx: 12px;
  cy: 4.5px;
  r: 1.75px;
}

</style>

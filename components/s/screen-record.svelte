<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="d7lirwbtl"/><circle class="aehem7bjh"/><path class="guhbvob-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:screen-record" {...props}></Icon>
<style>
:global(.aehem7bjh) {
  cx: 12px;
  cy: 10.25px;
  r: 2.75px;
}

:global(.d7lirwbtl) {
  width: 18.5px;
  height: 13px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

:global(.guhbvob-p) {
  d: path("M12 16.75v3.5m-3.75 0h7.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

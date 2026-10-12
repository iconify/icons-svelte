<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iu6zz442a"/><circle class="i9v4e1r8y"/><circle class="ispxgzbeo"/><rect class="nx0ee9b7r"/><path class="prqv4c02l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:weather-station-farm" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i9v4e1r8y) {
  cx: 5px;
  cy: 6px;
  r: 2.25px;
}

:global(.ispxgzbeo) {
  cx: 19px;
  cy: 6px;
  r: 2.25px;
}

:global(.iu6zz442a) {
  d: path("M12 21.25V6M6.5 6h11M8 21.25h8");
}

:global(.nx0ee9b7r) {
  width: 7px;
  height: 5.5px;
  x: 8.5px;
  y: 11px;
  rx: 1px;
}

:global(.prqv4c02l) {
  d: path("M8.5 13.75h7");
}

</style>

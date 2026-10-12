<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ydy0opbpr"/><circle class="o1cy2tblq"/><path class="qlu4-7b0e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:smart-button" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o1cy2tblq) {
  cx: 12px;
  cy: 15.5px;
  r: 2.75px;
}

:global(.qlu4-7b0e) {
  d: path("M6.38 8.8a8.75 8.75 0 0 1 11.24 0M4.45 6.5a11.75 11.75 0 0 1 15.1 0");
}

:global(.ydy0opbpr) {
  cx: 12px;
  cy: 15.5px;
  r: 5.75px;
}

</style>

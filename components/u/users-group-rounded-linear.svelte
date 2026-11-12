<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="xkqyiwblc"/><path class="sd8wznb3i"/><ellipse class="dt10bzeut"/><path class="hadyfyrdk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:users-group-rounded-linear" {...props}></Icon>
<style>
:global(.dt10bzeut) {
  cx: 9px;
  cy: 17px;
  rx: 7px;
  ry: 4px;
}

:global(.hadyfyrdk) {
  d: path("M18 14C19.7542 14.3847 21 15.3589 21 16.5C21 17.5293 19.9863 18.4229 18.5 18.8704");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sd8wznb3i) {
  d: path("M15 9C16.6569 9 18 7.65685 18 6C18 4.34315 16.6569 3 15 3");
}

:global(.xkqyiwblc) {
  cx: 9px;
  cy: 6px;
  r: 4px;
}

</style>

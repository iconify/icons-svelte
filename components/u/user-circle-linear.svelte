<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="lcfnqzkei"/><circle class="shu3xdl9q"/><path class="g2kki9-kx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-circle-linear" {...props}></Icon>
<style>
:global(.g2kki9-kx) {
  d: path("M17.9696 20C17.8105 17.1085 16.9252 15 12.0004 15C7.0757 15 6.1904 17.1085 6.03125 20");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lcfnqzkei) {
  cx: 12px;
  cy: 9px;
  r: 3px;
}

:global(.shu3xdl9q) {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vf_31rbpy"/><circle class="qv6z4dm_p"/><circle class="oicbsxx-q"/><circle class="s0kr5gbel"/><circle class="jwum6hb4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:scatter-chart-sharp" {...props}></Icon>
<style>
:global(.jwum6hb4u) {
  cx: 18px;
  cy: 7px;
  r: 1.5px;
}

:global(.oicbsxx-q) {
  cx: 12px;
  cy: 9.25px;
  r: 1.5px;
}

:global(.qv6z4dm_p) {
  cx: 8.75px;
  cy: 15.5px;
  r: 1.5px;
}

:global(.s0kr5gbel) {
  cx: 15.75px;
  cy: 14.5px;
  r: 1.5px;
}

:global(.vf_31rbpy) {
  d: path("M3.75 3.75v16.5h16.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

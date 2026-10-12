<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="v90gbqbox"/><circle class="gp0egaclj"/><circle class="peqyckbty"/><circle class="m7_yedtmn"/><circle class="jvsm0_ljk"/><circle class="lgmq2ebgl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:teething-ring-sharp" {...props}></Icon>
<style>
:global(.gp0egaclj) {
  cx: 12px;
  cy: 12px;
  r: 3px;
}

:global(.jvsm0_ljk) {
  cx: 6.85px;
  cy: 6.85px;
  r: 1.5px;
}

:global(.lgmq2ebgl) {
  cx: 17.15px;
  cy: 17.15px;
  r: 1.5px;
}

:global(.m7_yedtmn) {
  cx: 6.85px;
  cy: 17.15px;
  r: 1.5px;
}

:global(.peqyckbty) {
  cx: 17.15px;
  cy: 6.85px;
  r: 1.5px;
}

:global(.v90gbqbox) {
  cx: 12px;
  cy: 12px;
  r: 6px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

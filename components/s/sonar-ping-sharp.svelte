<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="svuooibzi"/><path class="siwf3tbbo"/><circle class="taq4_hb2a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sonar-ping-sharp" {...props}></Icon>
<style>
:global(.siwf3tbbo) {
  d: path("M8.5 8.25a5.25 5.25 0 0 1 0 7.5m3-10.5a9.5 9.5 0 0 1 0 13.5");
}

:global(.svuooibzi) {
  cx: 4.75px;
  cy: 12px;
  r: 2px;
}

:global(.taq4_hb2a) {
  cx: 18.75px;
  cy: 12px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

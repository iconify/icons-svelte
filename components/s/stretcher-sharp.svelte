<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="epmaifbxu"/><circle class="b1g9m1bqw"/><circle class="otw2wcc-c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:stretcher-sharp" {...props}></Icon>
<style>
:global(.b1g9m1bqw) {
  cx: 7px;
  cy: 19.5px;
  r: 1.5px;
}

:global(.epmaifbxu) {
  d: path("M6 8h12M2.75 11h18.5M7 11v7m10-7v7");
}

:global(.otw2wcc-c) {
  cx: 17px;
  cy: 19.5px;
  r: 1.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

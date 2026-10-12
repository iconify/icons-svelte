<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jfp291brm"/><circle class="ygphxfbhc"/><path class="ozy1wf4nb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ungroup-objects-sharp" {...props}></Icon>
<style>
:global(.jfp291brm) {
  d: path("M2.75 2.75h8v8h-8z");
}

:global(.ozy1wf4nb) {
  d: path("M16.5 2.75h4.75V7.5m-18.5 9v4.75H7.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ygphxfbhc) {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
}

</style>

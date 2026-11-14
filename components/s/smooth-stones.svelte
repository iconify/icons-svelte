<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tfsrfuvdq"/><path class="q0mz0bimm"/><path class="fhk_jqo4q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:smooth-stones" {...props}></Icon>
<style>
:global(.fhk_jqo4q) {
  d: path("M8.5 5.75a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0Z");
}

:global(.q0mz0bimm) {
  d: path("M10.5 7.5a6 3 0 1 0 3 0");
}

:global(.tfsrfuvdq) {
  d: path("M15 13a8.5 3.5 0 1 1-6 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

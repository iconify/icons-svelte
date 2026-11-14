<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kcs_d0bqk"/><path class="q5w2-zbce"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tree-check" {...props}></Icon>
<style>
:global(.kcs_d0bqk) {
  d: path("M3.5 8.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0ZM10 15v6.5");
}

:global(.q5w2-zbce) {
  d: path("M10 13v-2.5L12.5 8m2.25 10l2 2L21 15.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

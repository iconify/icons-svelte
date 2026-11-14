<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jky2v4bad"/><path class="gkhdp4bho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:wind-gentle-breeze" {...props}></Icon>
<style>
:global(.gkhdp4bho) {
  d: path("M4.5 9q0-4 4-4q0 4-4 4Z");
}

:global(.jky2v4bad) {
  d: path("M3 9h12a3 3 0 1 0-3-3m-9 9h14.5a3 3 0 1 1-3 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

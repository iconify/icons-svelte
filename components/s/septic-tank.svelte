<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l_--bg86l"/><path class="nzrn7sb2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:septic-tank" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l_--bg86l) {
  d: path("M7.75 11.5h8.5A4.75 4.75 0 0 1 21 16.25A4.75 4.75 0 0 1 16.25 21h-8.5A4.75 4.75 0 0 1 3 16.25a4.75 4.75 0 0 1 4.75-4.75m-5.25-5h9m4-4v9m-2-9h4");
}

:global(.nzrn7sb2l) {
  d: path("M5.5 16q3-1.5 6 0c2 1 4 1 7 0");
}

</style>

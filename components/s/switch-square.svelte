<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wt8i23w3i"/><path class="b5n-e_a4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:switch-square" {...props}></Icon>
<style>
:global(.b5n-e_a4s) {
  d: path("M14.875 8.75h1.25a2.625 2.625 0 0 1 2.625 2.625v1.25a2.625 2.625 0 0 1-2.625 2.625h-1.25a2.625 2.625 0 0 1-2.625-2.625v-1.25a2.625 2.625 0 0 1 2.625-2.625");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wt8i23w3i) {
  d: path("M7.75 5.5h8.5a5.25 5.25 0 0 1 5.25 5.25v2.5a5.25 5.25 0 0 1-5.25 5.25h-8.5a5.25 5.25 0 0 1-5.25-5.25v-2.5A5.25 5.25 0 0 1 7.75 5.5");
}

</style>

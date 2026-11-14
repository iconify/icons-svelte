<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r2cx5_i_e"/><path class="wo0e5vqgc"/><path class="zpyo8wbkc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:torus" {...props}></Icon>
<style>
:global(.r2cx5_i_e) {
  d: path("M2.5 12a9.5 6.5 0 1 0 19 0a9.5 6.5 0 1 0-19 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wo0e5vqgc) {
  d: path("M7.5 11c2.25 2.25 6.75 2.25 9 0");
}

:global(.zpyo8wbkc) {
  d: path("M9 12.25c1.5-1 4.5-1 6 0");
}

</style>

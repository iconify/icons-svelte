<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i8l-vra6m"/><path class="ysza2bc_q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:specimen-preserved" {...props}></Icon>
<style>
:global(.i8l-vra6m) {
  d: path("M7 2.5h10V6H7ZM8 6L5 9v10a2.5 2.5 0 0 0 2.5 2.5h9A2.5 2.5 0 0 0 19 19V9l-3-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ysza2bc_q) {
  d: path("M9.5 18c0-5 3-7.5 5-7.5c0 5-2.5 7.5-5 7.5Z");
}

</style>

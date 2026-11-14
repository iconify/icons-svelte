<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hp9ld3byv"/><path class="feha28aaq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:viewport" {...props}></Icon>
<style>
:global(.feha28aaq) {
  d: path("M6 14.5h12M8.5 12L6 14.5L8.5 17m7-5l2.5 2.5l-2.5 2.5");
}

:global(.hp9ld3byv) {
  d: path("M2.5 3.5h19v17h-19Zm0 4.5h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

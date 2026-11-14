<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="znqs3ybbt"/><path class="uoc1nyb0w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:store-moved" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uoc1nyb0w) {
  d: path("M3 9a3 3 0 0 0 6 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0M6.5 20.5v-5h4v5M14 18h1.25m2 0h4.25m-2.25-2.25L21.5 18l-2.25 2.25");
}

:global(.znqs3ybbt) {
  d: path("m3 9l1.5-5h15L21 9m-1.5 2v1.1M4.5 11v9.5h6.7");
}

</style>

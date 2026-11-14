<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x3uwmob_u"/><path class="s7v73ac1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:time-entry-done" {...props}></Icon>
<style>
:global(.s7v73ac1b) {
  d: path("m14.5 18l2.5 2.5l4.5-5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x3uwmob_u) {
  d: path("M14.1 21.5H4.5v-19h15v11.1m-15-6.1h15m-15 5h15m-10-5v14");
}

</style>

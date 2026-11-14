<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zu1iks2yj"/><path class="larev_2uk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:soda-glass" {...props}></Icon>
<style>
:global(.larev_2uk) {
  d: path("M8.5 11.25H13v4.5H8.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zu1iks2yj) {
  d: path("M5 6h14l-1.5 15h-11Zm10 11.5l3.5-15m-13 6h13");
}

</style>

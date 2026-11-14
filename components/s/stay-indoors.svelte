<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ke58ybbzd"/><path class="dw47zmpqy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:stay-indoors" {...props}></Icon>
<style>
:global(.dw47zmpqy) {
  d: path("M7.5 14.5H15m-3-3l3 3l-3 3");
}

:global(.ke58ybbzd) {
  d: path("M3.5 10.5L12 3.25l8.5 7.25v10h-17Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

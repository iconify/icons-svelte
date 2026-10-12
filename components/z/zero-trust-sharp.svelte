<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ch2x-summ"/><path class="j7vio8fah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:zero-trust-sharp" {...props}></Icon>
<style>
:global(.ch2x-summ) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.16 3.31a9.25 9.25 0 0 1 5.53 5.53m0 6.32a9.25 9.25 0 0 1-5.53 5.53m-6.32 0a9.25 9.25 0 0 1-5.53-5.53m0-6.32a9.25 9.25 0 0 1 5.53-5.53M8 11h8v6.5H8zm1.75 0V9.25a2.25 2.25 0 0 1 4.5 0V11");
}

:global(.j7vio8fah) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14.25h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

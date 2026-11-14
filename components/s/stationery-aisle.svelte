<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bnfy7ebex"/><path class="iuxl_9bdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:stationery-aisle" {...props}></Icon>
<style>
:global(.bnfy7ebex) {
  d: path("M2.5 2.5h19M7 2.5V7m10-4.5V7M2.5 7h19v13h-19Z");
}

:global(.iuxl_9bdu) {
  d: path("M6 16.5h10.5a3 3 0 0 0 0-6H8a2 2 0 0 0 0 4h7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

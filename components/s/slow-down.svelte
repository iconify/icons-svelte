<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kyy2if6za"/><path class="trfxszbrb"/><path class="j38utxbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:slow-down" {...props}></Icon>
<style>
:global(.j38utxbis) {
  d: path("M13 11a2.5 2.5 0 1 1-2.5-2.5");
}

:global(.kyy2if6za) {
  d: path("M5 10.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

:global(.trfxszbrb) {
  d: path("M2.5 16h15a2.5 2.5 0 0 0 2.5-2.5v-4m-1.25-3l1.25 3l1.5-2.75M3 19.5h18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

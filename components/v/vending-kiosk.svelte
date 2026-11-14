<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oeucrxbku"/><path class="koytlfb1l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:vending-kiosk" {...props}></Icon>
<style>
:global(.koytlfb1l) {
  d: path("M5.75 4.75h9v12.5h-9Zm4.5 0v12.5m-4.5-8.5h9m-9 4.25h9m3-6.5h.01M16.75 10h2M6.5 19.5H14");
}

:global(.oeucrxbku) {
  d: path("M3.5 2.5h17v19h-17Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

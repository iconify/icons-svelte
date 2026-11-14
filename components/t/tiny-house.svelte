<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="toa3gkblk"/><path class="es_d5xbfm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tiny-house" {...props}></Icon>
<style>
:global(.es_d5xbfm) {
  d: path("M7.5 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.5-3V13h2.5v3.5m4-4.5h.01");
}

:global(.toa3gkblk) {
  d: path("m3.5 10l6-6l6 6v6.5h-12Zm-1 6.5h14l5 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

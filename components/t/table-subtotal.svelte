<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nw3-gqk9b"/><path class="sm46k33lu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:table-subtotal" {...props}></Icon>
<style>
:global(.nw3-gqk9b) {
  d: path("M3 3h18v18H3Zm0 5h18M3 13h18M9 3v10m6-10v10");
}

:global(.sm46k33lu) {
  d: path("M11.5 15h-5L9 17l-2.5 2h5m2.5-2h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

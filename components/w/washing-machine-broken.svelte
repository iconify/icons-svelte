<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="baciku7_x"/><path class="jxz50xbgf"/><path class="u661a6bii"/><path class="x_9mjb4ow"/><path class="tq7kvx37d"/><path class="g4uzw-b-k"/><path class="c-qa2bcch"/><path class="n2pg5aclz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:washing-machine-broken" {...props}></Icon>
<style>
:global(.baciku7_x) {
  d: path("M6 22V21");
}

:global(.c-qa2bcch) {
  stroke-linejoin: round;
  d: path("M14.5 5.5H14.5001");
}

:global(.g4uzw-b-k) {
  d: path("M6.5 5.5H9.5");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jxz50xbgf) {
  d: path("M18 22V21");
}

:global(.n2pg5aclz) {
  stroke-linejoin: round;
  d: path("M17.5 5.5H17.5001");
}

:global(.tq7kvx37d) {
  d: path("M15 15C15 16.6569 13.6569 18 12 18C10.3431 18 9 16.6569 9 15C9 13.3431 10.3431 12 12 12C13.6569 12 15 13.3431 15 15Z");
}

:global(.u661a6bii) {
  d: path("M3 10C3 6.22876 3 4.34315 4.17157 3.17157C5.34315 2 7.22876 2 11 2H13C16.7712 2 18.6569 2 19.8284 3.17157C21 4.34315 21 6.22876 21 10V13C21 16.7712 21 18.6569 19.8284 19.8284C18.6569 21 16.7712 21 13 21H11C7.22876 21 5.34315 21 4.17157 19.8284C3.10848 18.7653 3.01004 17.1143 3.00093 14");
}

:global(.x_9mjb4ow) {
  d: path("M3 9H12M16 9H21");
}

</style>

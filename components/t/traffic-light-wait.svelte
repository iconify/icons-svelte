<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ry1sp5hjj"/><path class="k0xhhrggo"/><path class="qoy9xab8s"/><path class="xglnp1d1i"/><path class="a6k62accz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:traffic-light-wait" {...props}></Icon>
<style>
:global(.a6k62accz) {
  d: path("M18 16.5V18l1.25 1");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k0xhhrggo) {
  d: path("M6 6.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.qoy9xab8s) {
  fill: currentColor;
  d: path("M6 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.ry1sp5hjj) {
  d: path("M7.375 2h.25A4.375 4.375 0 0 1 12 6.375v11.25A4.375 4.375 0 0 1 7.625 22h-.25A4.375 4.375 0 0 1 3 17.625V6.375A4.375 4.375 0 0 1 7.375 2");
}

:global(.xglnp1d1i) {
  d: path("M6 17.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8.75.25a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>

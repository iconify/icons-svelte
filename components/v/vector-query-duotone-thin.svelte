<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ph4toqkti"/><path class="wko3ej0az"/><path class="r0oiw3llx"/><path class="s7h04rdua"/><path class="skm9b1j-d"/><path class="ls7ugdcwr"/><path class="fglxyivky"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vector-query-duotone-thin" {...props}></Icon>
<style>
:global(.fglxyivky) {
  d: path("M18 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ls7ugdcwr) {
  d: path("M6 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ph4toqkti) {
  fill: currentColor;
  d: path("M4 9a5 5 0 1 0 10 0A5 5 0 1 0 4 9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r0oiw3llx) {
  fill: currentColor;
  d: path("M18 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s7h04rdua) {
  d: path("M4 9a5 5 0 1 0 10 0A5 5 0 1 0 4 9");
}

:global(.skm9b1j-d) {
  d: path("m13 13 6 6");
}

:global(.wko3ej0az) {
  fill: currentColor;
  d: path("M6 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

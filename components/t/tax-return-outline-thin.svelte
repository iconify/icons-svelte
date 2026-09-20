<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y4_6s7b5v"/><path class="wuvisubmw"/><path class="gzg_qsbpe"/><path class="fxvoaub7q"/><path class="w82z55b-g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tax-return-outline-thin" {...props}></Icon>
<style>
:global(.fxvoaub7q) {
  d: path("m11 15 6 -6");
}

:global(.gzg_qsbpe) {
  d: path("M10.5 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w82z55b-g) {
  d: path("M15.5 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.wuvisubmw) {
  d: path("M8 3v18");
}

:global(.y4_6s7b5v) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="al80ij1va"/><path class="wv8fhiw3l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:saucepan" {...props}></Icon>
<style>
:global(.al80ij1va) {
  width: 12px;
  height: 12.75px;
  x: 2.75px;
  y: 8.5px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wv8fhiw3l) {
  d: path("M2.75 12h12m0-.5h6.5");
}

</style>

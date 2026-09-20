<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abchdfb3i"/><path class="uicwdzbry"/><path class="yl8oldl7l"/><path class="owdk3hf1a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tempo-outline-thin" {...props}></Icon>
<style>
:global(.abchdfb3i) {
  d: path("M4 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.owdk3hf1a) {
  d: path("m18 8 4 4 -4 4");
}

:global(.uicwdzbry) {
  d: path("M10 17V6");
}

:global(.yl8oldl7l) {
  d: path("m13 8 4 4 -4 4");
}

</style>

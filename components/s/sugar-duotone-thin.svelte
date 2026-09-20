<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ndtiqfb4f"/><path class="ueyyuelny"/><path class="izxeldb4t"/><path class="fg09jpbsd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sugar-duotone-thin" {...props}></Icon>
<style>
:global(.fg09jpbsd) {
  d: path("M13 5h8v8h-8Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.izxeldb4t) {
  d: path("M3 11h8v8H3Z");
}

:global(.ndtiqfb4f) {
  fill: currentColor;
  d: path("M3 11h8v8H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ueyyuelny) {
  fill: currentColor;
  d: path("M13 5h8v8h-8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

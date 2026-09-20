<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c_s6h8ded"/><path class="w_lu3fbkz"/><path class="i-2dnzb7m"/><path class="emvotkb4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:unpin-duotone-thin" {...props}></Icon>
<style>
:global(.c_s6h8ded) {
  fill: currentColor;
  d: path("M7 9a5 5 0 1 0 10 0A5 5 0 1 0 7 9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.emvotkb4z) {
  d: path("M4 20 20 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i-2dnzb7m) {
  d: path("M12 14v6");
}

:global(.w_lu3fbkz) {
  d: path("M7 9a5 5 0 1 0 10 0A5 5 0 1 0 7 9");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ut-qr0pxs"/><path class="tu8-ndo1t"/><path class="a6tpycbpp"/><path class="qw7b_6b1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:table-lamp-duotone-thin" {...props}></Icon>
<style>
:global(.a6tpycbpp) {
  d: path("M12 12v8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qw7b_6b1t) {
  d: path("M8 20h8");
}

:global(.tu8-ndo1t) {
  d: path("m4 12 5 -5h6l5 5Z");
}

:global(.ut-qr0pxs) {
  fill: currentColor;
  d: path("m4 12 5 -5h6l5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bkhodo2vo"/><path class="a6o0g3bee"/><path class="ka41iob5n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:telescope-outline-thin" {...props}></Icon>
<style>
:global(.a6o0g3bee) {
  d: path("m9 16 -4 4");
}

:global(.bkhodo2vo) {
  d: path("M5 14 15 4l4 4L9 18Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ka41iob5n) {
  d: path("m12 17 4 4");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zzbcrubdh"/><path class="c68dutvfq"/><path class="w28ybhbjm"/><path class="h7bcztycq"/><path class="h0r-78wsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:working-memory-duotone-thin" {...props}></Icon>
<style>
:global(.c68dutvfq) {
  d: path("M15 5h4a3 3 0 0 1 3 3v8a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h4");
}

:global(.h0r-78wsa) {
  d: path("M17 10v4");
}

:global(.h7bcztycq) {
  d: path("M12 8v8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w28ybhbjm) {
  d: path("M7 10v4");
}

:global(.zzbcrubdh) {
  fill: currentColor;
  d: path("M15 5h4a3 3 0 0 1 3 3v8a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

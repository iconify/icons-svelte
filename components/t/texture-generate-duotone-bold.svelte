<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zp7m0nbel"/><path class="sf7s7wb6x"/><path class="n2j__bcmh"/><path class="miofc3chu"/><path class="aig5gcc6s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:texture-generate-duotone-bold" {...props}></Icon>
<style>
:global(.aig5gcc6s) {
  d: path("m12 17 5 -5");
}

:global(.miofc3chu) {
  d: path("m9 15 6 -6");
}

:global(.n2j__bcmh) {
  d: path("m7 12 4 -4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sf7s7wb6x) {
  d: path("m12 2 6 6v8l-6 6 -6 -6V8Z");
}

:global(.zp7m0nbel) {
  fill: currentColor;
  d: path("m12 2 6 6v8l-6 6 -6 -6V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

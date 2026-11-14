<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v92itefcf"/><path class="wi2hd2blk"/><path class="hb6qfkhrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:subwoofer" {...props}></Icon>
<style>
:global(.hb6qfkhrs) {
  d: path("M10.25 11.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v92itefcf) {
  d: path("M6.5 4h11A3.5 3.5 0 0 1 21 7.5V15a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 15V7.5A3.5 3.5 0 0 1 6.5 4M6 18.5v2m12-2v2");
}

:global(.wi2hd2blk) {
  d: path("M7.25 11.25a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0");
}

</style>

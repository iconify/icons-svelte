<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ddgz2b25r"/><path class="zptogsb5s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:turn-sharp-right" {...props}></Icon>
<style>
:global(.ddgz2b25r) {
  d: path("M6.5 20.5V4l11 11");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zptogsb5s) {
  d: path("M17.5 9.5V15H12");
}

</style>

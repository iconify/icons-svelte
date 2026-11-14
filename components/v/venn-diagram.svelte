<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ztlf0zb4l"/><path class="epebwab_s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:venn-diagram" {...props}></Icon>
<style>
:global(.epebwab_s) {
  d: path("M9 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ztlf0zb4l) {
  d: path("M2 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

</style>

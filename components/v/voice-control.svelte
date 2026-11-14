<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m0v9koblw"/><path class="dz4oksbag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:voice-control" {...props}></Icon>
<style>
:global(.dz4oksbag) {
  d: path("M6.5 10.5a5.5 5.5 0 0 0 11 0M12 16v4.5m-9-14v5m18-5v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m0v9koblw) {
  d: path("M12 3za2.5 2.5 0 0 1 2.5 2.5v5A2.5 2.5 0 0 1 12 13a2.5 2.5 0 0 1-2.5-2.5v-5A2.5 2.5 0 0 1 12 3");
}

</style>

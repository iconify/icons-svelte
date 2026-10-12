<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="v7avk1-hg"/><path class="h93ukxbmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:video-library" {...props}></Icon>
<style>
:global(.h93ukxbmk) {
  d: path("M6.75 3.75h11.5a3 3 0 0 1 3 3v10M9.43 12.42l2.64 1.66q.68.42 0 .84l-2.64 1.66q-.68.42-.68-.38v-3.4q0-.8.68-.38");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v7avk1-hg) {
  width: 15.5px;
  height: 13.5px;
  x: 2.75px;
  y: 7.75px;
  rx: 2.5px;
}

</style>

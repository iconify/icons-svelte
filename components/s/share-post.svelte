<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="tqj6lmj3z"/><circle class="y56pw2b3p"/><circle class="i2799mjyd"/><path class="nh_j4ibuz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:share-post" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i2799mjyd) {
  cx: 17.5px;
  cy: 18.5px;
  r: 2.5px;
}

:global(.nh_j4ibuz) {
  d: path("m9.3 10.35l5.4-3.2m-5.4 6.5l5.4 3.2");
}

:global(.tqj6lmj3z) {
  cx: 17.5px;
  cy: 5.5px;
  r: 2.5px;
}

:global(.y56pw2b3p) {
  cx: 6.5px;
  cy: 12px;
  r: 2.5px;
}

</style>

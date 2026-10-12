<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rknchmb5r"/><path class="l4fy70bwr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:user-vip" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l4fy70bwr) {
  d: path("M4 20.25h11a.75.75 0 0 0 .75-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5a.75.75 0 0 0 .75.75M16.23 8.67l.79-1.09q.23-.33.63-.33h1.95q.4 0 .63.33l.79 1.09q.23.33-.01.65l-2.17 2.86q-.24.32-.48 0l-2.12-2.86Q16 9 16.23 8.67");
}

:global(.rknchmb5r) {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
}

</style>

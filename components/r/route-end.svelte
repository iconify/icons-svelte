<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="aldfehmne"/><path class="fc9xx45ab"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:route-end" {...props}></Icon>
<style>
:global(.aldfehmne) {
  cx: 4.75px;
  cy: 19px;
  r: 2px;
}

:global(.fc9xx45ab) {
  d: path("M6.75 19h5c2.5 0 4.25-1.75 4.25-4.25v-7m.68-4.68l3.89 1.86q.68.32 0 .64l-3.89 1.86Q16 7.75 16 7V3.5q0-.75.68-.43");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

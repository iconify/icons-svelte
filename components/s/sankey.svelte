<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="oij_xbccr"/><rect class="foujtlbte"/><rect class="kebrm_8wg"/><path class="e--1ehb5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sankey" {...props}></Icon>
<style>
:global(.e--1ehb5o) {
  d: path("M6.25 9c6 0 5.5-3 11.5-3m-11.5 9c6 0 5.5 3 11.5 3");
}

:global(.foujtlbte) {
  width: 3.5px;
  height: 6.5px;
  x: 17.75px;
  y: 2.75px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kebrm_8wg) {
  width: 3.5px;
  height: 6.5px;
  x: 17.75px;
  y: 14.75px;
  rx: 1px;
}

:global(.oij_xbccr) {
  width: 3.5px;
  height: 12.5px;
  x: 2.75px;
  y: 5.75px;
  rx: 1px;
}

</style>

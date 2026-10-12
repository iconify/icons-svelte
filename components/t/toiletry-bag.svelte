<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qx003y-do"/><rect class="cb1l2mm0i"/><rect class="kovi8mbiq"/><path class="dghy4xbte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:toiletry-bag" {...props}></Icon>
<style>
:global(.cb1l2mm0i) {
  width: 4px;
  height: 4.5px;
  x: 13.5px;
  y: 4.75px;
  rx: 1.25px;
}

:global(.dghy4xbte) {
  d: path("M2.75 12.75h18.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kovi8mbiq) {
  width: 18.5px;
  height: 12px;
  x: 2.75px;
  y: 9.25px;
  rx: 3.5px;
}

:global(.qx003y-do) {
  d: path("M9 9.25L7.25 3.5");
}

</style>

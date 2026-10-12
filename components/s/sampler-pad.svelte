<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a_-q_pb0z"/><path class="rqjlqxbxo"/><rect class="xrs144bol"/><rect class="q12y57b_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sampler-pad" {...props}></Icon>
<style>
:global(.a_-q_pb0z) {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 3px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q12y57b_j) {
  width: 4.5px;
  height: 4.5px;
  x: 13.75px;
  y: 13.5px;
  rx: 1px;
}

:global(.rqjlqxbxo) {
  d: path("M6.25 8.25H8l1.5-2.5l2 5l2-5l1.5 2.5h2.75");
}

:global(.xrs144bol) {
  width: 4.5px;
  height: 4.5px;
  x: 5.75px;
  y: 13.5px;
  rx: 1px;
}

</style>

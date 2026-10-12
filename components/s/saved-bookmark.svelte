<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a_-q_pb0z"/><path class="wiwhvjb_z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:saved-bookmark" {...props}></Icon>
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

:global(.wiwhvjb_z) {
  d: path("M14 2.75h4.5v7.5c0 .45-.5.7-.85.45l-1.4-1.05l-1.4 1.05a.54.54 0 0 1-.85-.45ZM6.5 8H11m-4.5 5.5h11m-11 3.75h8");
}

</style>

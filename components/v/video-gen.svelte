<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mza817zhn"/><path class="xzjtmzrol"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:video-gen" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mza817zhn) {
  width: 12px;
  height: 12px;
  x: 2.75px;
  y: 6px;
  rx: 2.5px;
}

:global(.xzjtmzrol) {
  d: path("m18.36 9.81l2.28-1.62q.61-.44.61.31v7q0 .75-.61.31l-2.28-1.62q-.61-.44-.61-1.19v-2q0-.75.61-1.19M8.75 8.5q.42 3.08 3.5 3.5q-3.08.42-3.5 3.5q-.42-3.08-3.5-3.5q3.08-.42 3.5-3.5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zj2jvpbmh"/><path class="ctt9_pbte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:video-download" {...props}></Icon>
<style>
:global(.ctt9_pbte) {
  d: path("m16.61 9.74l3.78-2.23q.86-.51.86.49v8q0 1-.86.49l-3.78-2.23q-.86-.51-.86-1.51v-1.5q0-1 .86-1.51");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zj2jvpbmh) {
  width: 13px;
  height: 12.5px;
  x: 2.75px;
  y: 5.75px;
  rx: 2.5px;
}

</style>

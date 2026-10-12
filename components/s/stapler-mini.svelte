<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rhml0w0_u"/><rect class="gzjv-ukxe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:stapler-mini" {...props}></Icon>
<style>
:global(.gzjv-ukxe) {
  width: 16.5px;
  height: 4.5px;
  x: 3.75px;
  y: 14.75px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rhml0w0_u) {
  d: path("M6.5 6.75h9q1.75 0 2.72 1.46l.06.08q.97 1.46.97 2.46t-1.75 1h-11q-1.75 0-1.75-1.75V8.5q0-1.75 1.75-1.75m.5 5v3");
}

</style>

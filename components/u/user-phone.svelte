<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rknchmb5r"/><path class="kf_mvwa8r"/><rect class="fvf_2kbgo"/><path class="tixlsxbin"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:user-phone" {...props}></Icon>
<style>
:global(.fvf_2kbgo) {
  width: 4.75px;
  height: 8.25px;
  x: 16.25px;
  y: 5.75px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kf_mvwa8r) {
  d: path("M4 20.25h11a.75.75 0 0 0 .75-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5a.75.75 0 0 0 .75.75");
}

:global(.rknchmb5r) {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
}

:global(.tixlsxbin) {
  d: path("M18 11.25h1.25");
}

</style>

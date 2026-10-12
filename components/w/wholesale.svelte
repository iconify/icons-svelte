<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="u2cta0s5d"/><rect class="n2k71vb3o"/><rect class="j3zcwcc5d"/><path class="mxsp25f_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wholesale" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j3zcwcc5d) {
  width: 7.5px;
  height: 5.5px;
  x: 8.25px;
  y: 4.5px;
  rx: 1.25px;
}

:global(.mxsp25f_j) {
  d: path("M6.5 13v2.5m11-2.5v2.5M12 4.5V7M2.75 21.25h18.5");
}

:global(.n2k71vb3o) {
  width: 7.5px;
  height: 5.5px;
  x: 13.75px;
  y: 13px;
  rx: 1.25px;
}

:global(.u2cta0s5d) {
  width: 7.5px;
  height: 5.5px;
  x: 2.75px;
  y: 13px;
  rx: 1.25px;
}

</style>

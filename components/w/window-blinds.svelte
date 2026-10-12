<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sz57t6b-v"/><rect class="rruwowb6k"/><path class="u6kw3w_ie"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:window-blinds" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rruwowb6k) {
  width: 15.5px;
  height: 13px;
  x: 4.25px;
  y: 3.75px;
  rx: 1px;
}

:global(.sz57t6b-v) {
  d: path("M2.75 3.75h18.5");
}

:global(.u6kw3w_ie) {
  d: path("M4.25 8h15.5m-15.5 4.5h15.5m-3.25 4.25v4.5");
}

</style>

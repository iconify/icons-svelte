<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="bw_d33bcd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:trademark-symbol" {...props}></Icon>
<style>
:global(.bw_d33bcd) {
  d: path("M6.5 9h5M9 9v6.5m4 0V9l2.25 3.5L17.5 9v6.5");
}

:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

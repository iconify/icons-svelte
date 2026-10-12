<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qcl45yb5w"/><path class="h9iv7nbwx"/><circle class="lb_5ccc9w"/><path class="cn7l77bpv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:savings" {...props}></Icon>
<style>
:global(.cn7l77bpv) {
  d: path("M13.13 6.52c-.21-.45-.62-.75-1.12-.75c-.67 0-1.17.39-1.17.86c0 1.22 2.34.61 2.34 1.78c0 .49-.5.83-1.17.83c-.52 0-.96-.28-1.14-.73");
}

:global(.h9iv7nbwx) {
  d: path("M8.75 16.25h6.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lb_5ccc9w) {
  cx: 12px;
  cy: 7.5px;
  r: 4px;
}

:global(.qcl45yb5w) {
  width: 16.5px;
  height: 9.75px;
  x: 3.75px;
  y: 11.5px;
  rx: 2.5px;
}

</style>

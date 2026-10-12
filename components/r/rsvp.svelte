<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ack3h6b1o"/><path class="t1372hlxd"/><circle class="upu83lbfh"/><path class="o69111nsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rsvp" {...props}></Icon>
<style>
:global(.ack3h6b1o) {
  width: 16.5px;
  height: 13.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o69111nsa) {
  d: path("m15.25 17l1.25 1.25l2.5-2.5");
}

:global(.t1372hlxd) {
  d: path("M6.5 8h8m-8 3.5H11");
}

:global(.upu83lbfh) {
  cx: 17px;
  cy: 17px;
  r: 4.25px;
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="pap2ucgrx"/><path class="yu5lnvgmq"/><circle class="o80478h4m"/><path class="j4f4djbzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:security-tag" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j4f4djbzt) {
  d: path("M6.25 14h4");
}

:global(.o80478h4m) {
  cx: 15.5px;
  cy: 14px;
  r: 1.75px;
}

:global(.pap2ucgrx) {
  width: 18.5px;
  height: 8.5px;
  x: 2.75px;
  y: 9.75px;
  rx: 4.25px;
}

:global(.yu5lnvgmq) {
  d: path("M15.5 3.75v6");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dn_wzj_8e"/><circle class="p1q0e8bjj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wind-turbine" {...props}></Icon>
<style>
:global(.dn_wzj_8e) {
  d: path("M11.7 12.75h.6q.6 0 .68.6l.94 7.3q.08.6-.52.6h-2.8q-.6 0-.52-.6l.94-7.3q.08-.6.68-.6m.3-5.5V3m2.38 8.38l3.68 2.12m-8.44-2.12L5.94 13.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p1q0e8bjj) {
  cx: 12px;
  cy: 10px;
  r: 1.5px;
}

</style>

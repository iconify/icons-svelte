<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="zv0jcqhnw"/><path class="kh53oc2ob"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tai-chi" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kh53oc2ob) {
  d: path("M11 7.5v5m0 0L7 16v5.25m4-8.75l4.5 2.75l1.75 6M11 8.5l4 2l3.5-1.25M11 8.5l-3.75.75L5.5 7.5");
}

:global(.zv0jcqhnw) {
  cx: 11px;
  cy: 4.75px;
  r: 2px;
}

</style>

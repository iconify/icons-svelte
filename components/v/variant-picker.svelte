<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="o22ei45em"/><circle class="lygk6dbzl"/><circle class="v_866gg1g"/><circle class="z7ey_acuf"/><path class="rvgwq1bxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:variant-picker" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lygk6dbzl) {
  cx: 16.5px;
  cy: 7.5px;
  r: 3px;
}

:global(.o22ei45em) {
  cx: 7.5px;
  cy: 7.5px;
  r: 3px;
}

:global(.rvgwq1bxd) {
  d: path("m15 16.6l1 1l2-2.2");
}

:global(.v_866gg1g) {
  cx: 7.5px;
  cy: 16.5px;
  r: 3px;
}

:global(.z7ey_acuf) {
  cx: 16.5px;
  cy: 16.5px;
  r: 3.5px;
}

</style>

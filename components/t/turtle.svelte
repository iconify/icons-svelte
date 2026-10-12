<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zpnd_yrso"/><circle class="t_3yy3r3h"/><path class="ic9iewbqu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:turtle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ic9iewbqu) {
  d: path("M6 16.25v3m9.5-3v3m-8.75-3l1.5-4.5h5l1.5 4.5m-6.5-4.5L7 8.75m6.25 3l1.25-3");
}

:global(.t_3yy3r3h) {
  cx: 19.25px;
  cy: 13.5px;
  r: 2px;
}

:global(.zpnd_yrso) {
  d: path("M2.75 15.5c0-4.5 3.5-8 8-8s8 3.5 8 8a.75.75 0 0 1-.75.75H3.5a.75.75 0 0 1-.75-.75");
}

</style>

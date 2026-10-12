<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ixm9b82zq"/><circle class="t3wpecpwg"/><path class="u9ss38v1g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:trackball" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ixm9b82zq) {
  d: path("M2.75 15.25a6.5 6.5 0 0 1 6.5-6.5h5.5a6.5 6.5 0 0 1 6.5 6.5v3a3 3 0 0 1-3 3H5.75a3 3 0 0 1-3-3Z");
}

:global(.t3wpecpwg) {
  cx: 9.25px;
  cy: 15px;
  r: 3.25px;
}

:global(.u9ss38v1g) {
  d: path("M16.75 12.25v3.5");
}

</style>

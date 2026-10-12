<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="p_rn8pbth"/><path class="m-qubib1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:skeleton-loader" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m-qubib1j) {
  d: path("M13 5.75h8.25M13 9.25h5m-15.25 6.5h18.5m-18.5 4h12");
}

:global(.p_rn8pbth) {
  cx: 6.5px;
  cy: 7.5px;
  r: 3.75px;
}

</style>

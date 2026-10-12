<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="xglklabzt"/><path class="ngayx2bsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:time-off" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ngayx2bsa) {
  d: path("M12 7.5V12H8.5M3.75 3.75l16.5 16.5");
}

:global(.xglklabzt) {
  cx: 12px;
  cy: 12px;
  r: 8.5px;
}

</style>

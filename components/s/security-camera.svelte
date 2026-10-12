<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="da7clwbqd"/><circle class="t-z7r0bos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:security-camera" {...props}></Icon>
<style>
:global(.da7clwbqd) {
  d: path("M3.75 5.75h16.5m-15.5 3.5h14.5v2.5a7.25 7.25 0 0 1-14.5 0Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t-z7r0bos) {
  cx: 12px;
  cy: 14.25px;
  r: 2.25px;
}

</style>

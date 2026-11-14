<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eclq2vbmh"/><path class="jue--d_rz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:run-of-river" {...props}></Icon>
<style>
:global(.eclq2vbmh) {
  d: path("M3.5 13.25a8.5 8.5 0 0 1 17 0M12 4.75v8.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jue--d_rz) {
  d: path("m6 7.25l6 6l6-6M2.5 17.75q2.375-2.5 4.75 0t4.75 0t4.75 0t4.75 0");
}

</style>

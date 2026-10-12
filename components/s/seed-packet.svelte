<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zpv0_8b3o"/><path class="g-7ccccnr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:seed-packet" {...props}></Icon>
<style>
:global(.g-7ccccnr) {
  d: path("M12 14.25c0-2.5-1.5-4-4-4c0 2.5 1.5 4 4 4m0-1.75c0-2.5 1.5-4 4-4c0 2.5-1.5 4-4 4m0 1.75v1.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zpv0_8b3o) {
  d: path("M4.75 5.5L6.5 4.25L8.25 5.5L10 4.25l1.75 1.25l1.75-1.25l1.75 1.25L17 4.25l2 1.25v14.75a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1ZM8 17.75h8");
}

</style>

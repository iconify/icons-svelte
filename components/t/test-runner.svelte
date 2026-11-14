<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ib-ky-bwj"/><path class="v7h8rpsds"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:test-runner" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ib-ky-bwj) {
  d: path("M19.25 8.25A8.5 8.5 0 1 1 12 4");
}

:global(.v7h8rpsds) {
  d: path("m10 2l2 2l-2 2m4 2.5h.01m-1.26 2l-1.5 3.5l2.25 1.5l-.75 2m-1.5-3.5L9 15.5m.25-4.25l3.5-.75l2 2");
}

</style>

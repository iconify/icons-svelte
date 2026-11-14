<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rrkh46bbk"/><path class="cl6wyzb5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:scooter-wheel" {...props}></Icon>
<style>
:global(.cl6wyzb5d) {
  d: path("M10.5 16.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M12 15V3.5m-4 0h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rrkh46bbk) {
  d: path("M7 16.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

</style>

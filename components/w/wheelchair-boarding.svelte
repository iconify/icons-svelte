<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sggxjxb0v"/><path class="qxqw3_bzs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wheelchair-boarding" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qxqw3_bzs) {
  d: path("M11.75 9.103a4.5 4.5 0 1 1-6.147 6.147M2.5 22l19-3.5");
}

:global(.sggxjxb0v) {
  d: path("M9 3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M10.5 8v4H16l1.75 3.5");
}

</style>

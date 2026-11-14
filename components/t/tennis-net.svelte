<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcj6p99ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tennis-net" {...props}></Icon>
<style>
:global(.qcj6p99ql) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20V4m18 16V4M3 6.5q9 3 18 0M3 16q9 1.5 18 0M9.5 7.75v9m5-9v9");
}

</style>

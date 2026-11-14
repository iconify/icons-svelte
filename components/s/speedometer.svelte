<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrmgteblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:speedometer" {...props}></Icon>
<style>
:global(.lrmgteblx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.5a9.5 9.5 0 0 1 19 0M3.75 11.75L6 13m6-6v2.5m8.25 2.25L18 13m-6 3.5l3-5.25m-3 5.25h.01");
}

</style>

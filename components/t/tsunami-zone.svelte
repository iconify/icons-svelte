<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxy8s1b-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tsunami-zone" {...props}></Icon>
<style>
:global(.fxy8s1b-e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18.5c5 0 6.5-4 6.5-7.5c0-4.5 3.5-7.5 7.5-7.5c2.75 0 5 2 5 4.5c0 2-1.5 3.25-3 3.25s-2.5-1-2.5-2.5M2.5 21.5h10m5.5-6.75v3.5M18 21h.01");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe9w-zbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:terrain" {...props}></Icon>
<style>
:global(.qe9w-zbfw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25c2-4.5 4.75-7 8.25-7s6.5 2.5 10.25 3.5v3.5Zm0-7.75l5-7l3.5 4.75l2.5-3L17.5 12");
}

</style>

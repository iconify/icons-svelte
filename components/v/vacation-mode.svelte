<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwaka1yey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:vacation-mode" {...props}></Icon>
<style>
:global(.bwaka1yey) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21c0-5-1-8.5-2.5-11.5m0 0C8 7 5 6.5 3 8m6.5 1.5c.5-3 3-4.5 6-4m-6 4c3-.5 6 1 7.5 3.5M9.5 9.5C7 9.25 4.75 10.75 3.75 13m1.75 8h13");
}

</style>

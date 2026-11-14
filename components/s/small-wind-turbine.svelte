<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rt7x11bxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:small-wind-turbine" {...props}></Icon>
<style>
:global(.rt7x11bxl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9V2.5M12 9l-5.75 3.25M12 9l5.75 3.25M12 9v11.5m-4.5 0h9");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lladxqdzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:trophy" {...props}></Icon>
<style>
:global(.lladxqdzc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.5h10v6a5 5 0 0 1-10 0Zm0 2H5a2 2 0 0 0 0 4h2m10-4h2a2 2 0 0 1 0 4h-2m-5 5V20m-4 0h8");
}

</style>

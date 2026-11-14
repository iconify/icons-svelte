<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glxz7obxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tyre-wall" {...props}></Icon>
<style>
:global(.glxz7obxp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 16.25a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0m11.5 0a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0M7.75 6.5a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0m-1.5 9.75h.01m11.49 0h.01M12 6.5h.01");
}

</style>

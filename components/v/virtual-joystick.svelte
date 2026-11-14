<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8n0zybps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:virtual-joystick" {...props}></Icon>
<style>
:global(.k8n0zybps) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17a9.5 4 0 1 0 19 0a9.5 4 0 1 0-19 0M12 9.5V17M8.5 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>

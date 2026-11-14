<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g15ppgbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rugby-ball" {...props}></Icon>
<style>
:global(.g15ppgbaf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 19.5a13 13 0 0 1 15-15a13 13 0 0 1-15 15M9 15l6-6m-6 4l2 2m0-4l2 2m0-4l2 2");
}

</style>

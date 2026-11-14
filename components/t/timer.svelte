<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjkq2o5tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:timer" {...props}></Icon>
<style>
:global(.wjkq2o5tm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 13a8 8 0 1 0 16 0a8 8 0 1 0-16 0M9.5 2.5h5M12 13V8.5");
}

</style>

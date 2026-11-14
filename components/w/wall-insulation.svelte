<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhwj-uhkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wall-insulation" {...props}></Icon>
<style>
:global(.yhwj-uhkj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5v19m14-19v19M7.75 3l8.5 3.5l-8.5 3.5l8.5 3.5l-8.5 3.5l8.5 3.5");
}

</style>

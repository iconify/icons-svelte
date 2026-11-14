<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x83opqblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:stair-stringer" {...props}></Icon>
<style>
:global(.x83opqblh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 21H3v-4h3.75v-3.5h3.5V10h3.5V6.5h3.5V3H21v4.75m0 0L7.75 21");
}

</style>

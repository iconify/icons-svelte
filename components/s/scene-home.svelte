<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1tew_bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:scene-home" {...props}></Icon>
<style>
:global(.q1tew_bds) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 17.5v-15h9v15zL3.75 19V4l4.5-1.5m0 15l2.5 4h10l-3.5-4");
}

</style>

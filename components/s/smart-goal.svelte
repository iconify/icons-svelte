<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxzooxbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:smart-goal" {...props}></Icon>
<style>
:global(.bxzooxbvy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 12a4.25 4.25 0 1 0 8.5 0A4.25 4.25 0 1 0 2 12m4.25 0h.01m7.24-7l2.25 2l4.75-3.5m-7 8l2.25 2L20.5 10m-7 8l2.25 2l4.75-3.5");
}

</style>

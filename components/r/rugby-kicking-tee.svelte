<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5ommobxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rugby-kicking-tee" {...props}></Icon>
<style>
:global(.j5ommobxt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5A7.5 7.5 0 0 1 12 16a7.5 7.5 0 0 1 0-13.5m-5 19h10L14.5 16h-5Zm5-15.25v6m-1.25-4.5h2.5m-2.5 3h2.5");
}

</style>

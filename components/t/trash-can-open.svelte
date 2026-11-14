<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvq5-xq2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:trash-can-open" {...props}></Icon>
<style>
:global(.bvq5-xq2b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 9L7 21h10l1.5-12Zm13 0L7 3m3 9.5v5m4-5v5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3_wqbb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:session-code" {...props}></Icon>
<style>
:global(.e3_wqbb4w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h19v13.5h-19ZM12 16.5v4m-4.5 0h9M6.75 9.75h.01m3.49 0h.01m3.49 0h.01m3.49 0h.01");
}

</style>

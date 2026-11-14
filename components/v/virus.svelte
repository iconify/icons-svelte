<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzo7z8_8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:virus" {...props}></Icon>
<style>
:global(.nzo7z8_8e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0ZM12 6.5V3m0 14.5V21m-5.5-9H3m14.5 0H21m-5-4l2.25-2.25M8 8L5.75 5.75M16 16l2.25 2.25M8 16l-2.25 2.25M10.5 11h.01m2.99 2.5h.01");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpqkrgb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:weathervane" {...props}></Icon>
<style>
:global(.qpqkrgb9j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.5L5.25 6l-2.5 2.5M5.25 6h12M12 6v15.25M8 13h8m-7 8.25h6m5.83-15.52l-3.41-2.21q-.42-.27-.42.23v4.5q0 .5.42.23l3.41-2.21q.42-.27 0-.54");
}

</style>

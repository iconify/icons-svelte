<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hioeeo6ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:star-outline-round" {...props}></Icon>
<style>
:global(.hioeeo6ii) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 3.25l2.25 6.25l6.5.25l-5.25 4l2 6.25l-5.5-3.75L6.5 20l2-6.25l-5.25-4l6.5-.25Z");
}

</style>

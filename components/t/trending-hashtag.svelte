<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4emjssly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:trending-hashtag" {...props}></Icon>
<style>
:global(.l4emjssly) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 3v11.25m5-11.25v11.25M3 7.25h11.25M3 12.25h11.25M15 21l6-6m-3.5 0H21v3.5");
}

</style>

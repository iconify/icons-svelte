<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkbjpb_wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:streamer-ribbon" {...props}></Icon>
<style>
:global(.pkbjpb_wj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.25h18.5M6 3.25C4.25 5.5 7.75 6.5 6 8.75s1.75 3.25 0 5.5s1.75 3.25 0 5.5m6-16.5c-1.75 2.25 1.75 3.25 0 5.5s1.75 3.25 0 5.5s1.75 3.25 0 5.5m6-16.5c-1.75 2.25 1.75 3.25 0 5.5s1.75 3.25 0 5.5");
}

</style>

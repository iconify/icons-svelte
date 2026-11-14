<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xz-kjebqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sprint-at-risk" {...props}></Icon>
<style>
:global(.xz-kjebqu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 3.5l6.5 7l-6.5 7m7-14l6.5 7l-6.5 7m9-5V17m0 3.5h.01");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t65ei5s-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:scissors" {...props}></Icon>
<style>
:global(.t65ei5s-z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 17.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m11 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-6-2.25L18 3.5m-2.5 11.75L6 3.5");
}

</style>

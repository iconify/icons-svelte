<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl7xddb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:what-if" {...props}></Icon>
<style>
:global(.wl7xddb-j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9h4m6 0h9m-15 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0m9.25 7.5c0-1.25 1-2 2.25-2s2.25.75 2.25 2C20.25 18 18 18 18 19.25m0 2.25h.01");
}

</style>

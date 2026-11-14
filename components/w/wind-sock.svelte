<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vt87-5bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wind-sock" {...props}></Icon>
<style>
:global(.vt87-5bxv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3v18.5M4 7a1.5 3.5 0 1 0 3 0a1.5 3.5 0 1 0-3 0m1.5-3.5l14 5m-14 2l14 2m-7-6.5v5.5");
}

</style>

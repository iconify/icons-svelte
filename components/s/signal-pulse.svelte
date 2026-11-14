<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfjlip0mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:signal-pulse" {...props}></Icon>
<style>
:global(.vfjlip0mo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19h5C9.5 19 10 9 12 9s2.5 10 4.5 10h5M12 5.5h.01");
}

</style>

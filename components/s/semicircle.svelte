<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly2t1hb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:semicircle" {...props}></Icon>
<style>
:global(.ly2t1hb2r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.75a9.5 9.5 0 0 1 19 0Z");
}

</style>

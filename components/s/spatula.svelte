<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogw5fvj5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:spatula" {...props}></Icon>
<style>
:global(.ogw5fvj5s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3.5h8V10H6Zm4 6.5v11M8 5.5V8m4-2.5V8");
}

</style>

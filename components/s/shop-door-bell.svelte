<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="didmesx0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shop-door-bell" {...props}></Icon>
<style>
:global(.didmesx0w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 16c0-6.5 2-9.5 5-9.5s5 3 5 9.5Zm-2.5 0h15M12 3v3.5m0 12.75h.01");
}

</style>

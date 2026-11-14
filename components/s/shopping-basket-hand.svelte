<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddlipnbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shopping-basket-hand" {...props}></Icon>
<style>
:global(.ddlipnbvd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10h18l-1.5 9a2 2 0 0 1-2 1.5h-11a2 2 0 0 1-2-1.5Zm4.5 0l3-6m6 6l-3-6");
}

</style>

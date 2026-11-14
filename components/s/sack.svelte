<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yb-ivmxxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sack" {...props}></Icon>
<style>
:global(.yb-ivmxxs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 4.5h8L15 8c4 2 5 6 4 10c-.5 2-3 3-7 3s-6.5-1-7-3c-1-4 0-8 4-10Zm0 0h8");
}

</style>

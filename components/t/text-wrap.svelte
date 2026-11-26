<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4o9o21wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:text-wrap" {...props}></Icon>
<style>
:global(.u4o9o21wf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3H21M3 9H18C19.6569 9 21 10.3431 21 12C21 13.6569 19.6569 15 18 15H12M14 13L12 15L14 17M3 15H8M3 21H15");
}

</style>

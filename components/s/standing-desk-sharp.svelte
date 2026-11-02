<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nujnjpbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:standing-desk-sharp" {...props}></Icon>
<style>
:global(.nujnjpbye) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20v-4h18v4M11 4h10v8H11Zm5 8v4M3 6l2-2l2 2m-4 4l2 2l2-2");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p018yidbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:snag-list" {...props}></Icon>
<style>
:global(.p018yidbg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5H21M9.5 12H21M9.5 19H21M3 3.5l3 3m0-3l-3 3m0 4l3 3m0-3l-3 3m0 4l3 3m0-3l-3 3");
}

</style>

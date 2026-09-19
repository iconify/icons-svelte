<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwd7vfb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-inbox" {...props}></Icon>
<style>
:global(.zwd7vfb4o) {
  fill: currentColor;
  d: path("M21 3H3.01v18H21zm-2 12h-4c0 1.66-1.35 3-3 3s-3-1.34-3-3H5V5h14z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8nq01z0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:server-24-filled" {...props}></Icon>
<style>
:global(.g8nq01z0z) {
  fill: currentColor;
  d: path("M9 2a3 3 0 0 0-3 3v14a3 3 0 0 0 3 3h6a3 3 0 0 0 3-3V5a3 3 0 0 0-3-3zm-.5 4.75A.75.75 0 0 1 9.25 6h5.5a.75.75 0 0 1 0 1.5h-5.5a.75.75 0 0 1-.75-.75m0 11a.75.75 0 0 1 .75-.75h5.5a.75.75 0 0 1 0 1.5h-5.5a.75.75 0 0 1-.75-.75m0-3a.75.75 0 0 1 .75-.75h5.5a.75.75 0 0 1 0 1.5h-5.5a.75.75 0 0 1-.75-.75");
}

</style>

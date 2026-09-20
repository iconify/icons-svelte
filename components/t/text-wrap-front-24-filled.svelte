<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxcb_r-pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-wrap-front-24-filled" {...props}></Icon>
<style>
:global(.nxcb_r-pf) {
  fill: currentColor;
  d: path("M3.75 3.75a1 1 0 0 0 0 2h16.5a1 1 0 1 0 0-2zm8.25 5c-.78 0-1.467.397-1.871 1H7.937a4.252 4.252 0 0 1 8.126 0h-2.192a2.25 2.25 0 0 0-1.871-1m-8.25 2a1 1 0 1 0 0 2h16.5a1 1 0 1 0 0-2zm4 3h2v2a1 1 0 1 1-2 0zm8.5 0h-2v2a1 1 0 1 0 2 0zm-13.5 5a1 1 0 0 1 1-1h16.5a1 1 0 1 1 0 2H3.75a1 1 0 0 1-1-1");
}

</style>

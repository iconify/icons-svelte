<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekq8dhbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-border-outer" {...props}></Icon>
<style>
:global(.ekq8dhbvn) {
  fill: currentColor;
  d: path("M13 7h-2v2h2zm0 4h-2v2h2zm4 0h-2v2h2zM3 3v18h18V3zm16 16H5V5h14zm-6-4h-2v2h2zm-4-4H7v2h2z");
}

</style>

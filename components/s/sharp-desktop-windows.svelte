<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jio770bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-desktop-windows" {...props}></Icon>
<style>
:global(.jio770bgp) {
  fill: currentColor;
  d: path("M23 2H1v16h9v2H8v2h8v-2h-2v-2h9zm-2 14H3V4h18z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo87yrbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-dvr" {...props}></Icon>
<style>
:global(.oo87yrbzj) {
  fill: currentColor;
  d: path("M23 3H1v16h7v2h8v-2h7zm-2 14H3V5h18zm-2-9H8v2h11zm0 4H8v2h11zM7 8H5v2h2zm0 4H5v2h2z");
}

</style>

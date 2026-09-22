<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urtkf_ipm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:sheets-column-swap-outline" {...props}></Icon>
<style>
:global(.urtkf_ipm) {
  fill: currentColor;
  d: path("M4 9V3h7v6zm2-2h3V5H6zm7 14V11h7v10zm2-2h3v-2h-3zm0-4h3v-2h-3zm-.5-6V7h2.075L14 4.425L15.4 3L18 5.6V3.5h2V9zM8.575 19L6 16.425V18.5H4V13h5.5v2H7.4l2.6 2.6z");
}

</style>

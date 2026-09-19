<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbz_v2bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-closed-caption-off" {...props}></Icon>
<style>
:global(.nbz_v2bkl) {
  fill: currentColor;
  d: path("M21 4H3v16h18zm-10 7H9.5v-.5h-2v3h2V13H11v2H6V9h5zm7 0h-1.5v-.5h-2v3h2V13H18v2h-5V9h5z");
}

</style>

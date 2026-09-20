<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omf6sab1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:signal-cellular-1-bar-sharp" {...props}></Icon>
<style>
:global(.omf6sab1k) {
  fill: currentColor;
  d: path("M3 21L21 3v18zm6.289-1H20V5.427L9.289 16.139z");
}

</style>

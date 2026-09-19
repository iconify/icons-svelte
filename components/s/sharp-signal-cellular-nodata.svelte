<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd0xe4a_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-signal-cellular-nodata" {...props}></Icon>
<style>
:global(.xd0xe4a_z) {
  fill: currentColor;
  d: path("M22 13h-9v9H2L22 2zm-1 2.41L19.59 14l-2.09 2.09L15.41 14L14 15.41l2.09 2.09L14 19.59L15.41 21l2.09-2.08L19.59 21L21 19.59l-2.08-2.09z");
}

</style>

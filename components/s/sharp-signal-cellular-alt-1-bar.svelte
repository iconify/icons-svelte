<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6cuozbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-signal-cellular-alt-1-bar" {...props}></Icon>
<style>
:global(.e6cuozbxd) {
  fill: currentColor;
  d: path("M5 14h3v6H5z");
}

</style>

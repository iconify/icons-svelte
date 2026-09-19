<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8vvoplie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-signal-cellular-alt-2-bar" {...props}></Icon>
<style>
:global(.a8vvoplie) {
  fill: currentColor;
  d: path("M5 14h3v6H5zm6-5h3v11h-3z");
}

</style>

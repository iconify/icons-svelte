<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wu2qubb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-vertical-align-bottom" {...props}></Icon>
<style>
:global(.wu2qubb-z) {
  fill: currentColor;
  d: path("M11 3v10H8l4 4l4-4h-3V3zM4 19h16v2H4z");
}

</style>

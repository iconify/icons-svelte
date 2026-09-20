<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbuwhob6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:top-panel-close-outline-sharp" {...props}></Icon>
<style>
:global(.qbuwhob6a) {
  fill: currentColor;
  d: path("M8.827 15.596h6.346L12 12.404zM5 8h14V5H5zm0 11h14V9H5zM5 8V5zM4 20V4h16v16z");
}

</style>

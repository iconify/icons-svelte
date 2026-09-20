<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydmdk9c9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:sound-detection-glass-break-sharp" {...props}></Icon>
<style>
:global(.ydmdk9c9w) {
  fill: currentColor;
  d: path("M4 15.712V4h16v2.935l-6.48 7.27l-4.02-4.018zM4 20v-2.712l5.5-5.525l3.98 3.981L20 8.434V20z");
}

</style>

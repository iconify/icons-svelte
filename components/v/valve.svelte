<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvz2oew5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:valve" {...props}></Icon>
<style>
:global(.mvz2oew5s) {
  fill: currentColor;
  d: path("M11.5 7.616v-3h-4v-1h9v1h-4v3zm-7 12.769v-7h1v1h4v-4h-1v-1h7v1h-1v4h4v-1h1v7h-1v-1h-13v1z");
}

</style>

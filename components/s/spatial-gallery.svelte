<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yex4rfg8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:spatial-gallery" {...props}></Icon>
<style>
:global(.yex4rfg8m) {
  fill: currentColor;
  d: path("M9.5 18.125V13h5v5.125zm0-7V6h5v5.125zm-7.5 0V4l5.5 1.575v5.55zM2 20v-7h5.5v5.55zm20 0l-5.5-1.45V13H22zm-5.5-8.875V5.6L22 4.125v7z");
}

</style>

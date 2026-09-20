<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyhonei6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:subtitles-sharp" {...props}></Icon>
<style>
:global(.uyhonei6b) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm4-4h8v-2H6zm10 0h2v-2h-2zM6 12h2v-2H6zm4 0h8v-2h-8z");
}

</style>

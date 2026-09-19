<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hh5k1f0eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-gif-box" {...props}></Icon>
<style>
:global(.hh5k1f0eu) {
  fill: currentColor;
  d: path("M21 3H3v18h18zM9.5 13v-1h1v2h-3v-4h3v1h-2v2zm3 1h-1v-4h1zm4-3h-2v.5H16v1h-1.5V14h-1v-4h3z");
}

</style>

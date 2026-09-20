<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="rtxt-ybyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:terminal-bold" {...props}></Icon>
<style>
:global(.rtxt-ybyi) {
  fill: currentColor;
  d: path("m120 137l-72 64a12 12 0 1 1-16-18l61.91-55L32 73a12 12 0 1 1 16-18l72 64a12 12 0 0 1 0 18m96 43h-96a12 12 0 0 0 0 24h96a12 12 0 0 0 0-24");
}

</style>

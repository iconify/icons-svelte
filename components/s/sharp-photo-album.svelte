<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu3o9obiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-photo-album" {...props}></Icon>
<style>
:global(.nu3o9obiz) {
  fill: currentColor;
  d: path("M20 2H4v20h16zm-9 2h5v7l-2.5-1.5L11 11zM7 18l2.38-3.17L11 17l2.62-3.5L17 18z");
}

</style>

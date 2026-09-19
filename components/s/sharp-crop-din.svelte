<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hodjzcbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-crop-din" {...props}></Icon>
<style>
:global(.hodjzcbue) {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-2 16H5V5h14z");
}

</style>

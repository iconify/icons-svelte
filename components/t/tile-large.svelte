<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5ltb1bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:tile-large" {...props}></Icon>
<style>
:global(.d5ltb1bxy) {
  fill: currentColor;
  d: path("M4 20v-4.75h6.616V20zm9.366 0v-4.75H20V20zM4 12.5V4h16v8.5z");
}

</style>

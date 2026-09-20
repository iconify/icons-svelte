<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne6qdwv4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:text-format-outline-sharp" {...props}></Icon>
<style>
:global(.ne6qdwv4h) {
  fill: currentColor;
  d: path("M5.5 18.539v-1h13v1zm2.112-3.77l3.907-10.308h1L16.35 14.77h-1.016l-1.026-2.838H9.666L8.627 14.77zm2.372-3.708h3.993l-1.908-5.28h-.1z");
}

</style>

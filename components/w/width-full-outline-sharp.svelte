<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar69pc4bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:width-full-outline-sharp" {...props}></Icon>
<style>
:global(.ar69pc4bh) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h1.423V6H4zm2.423 0h11.154V6H6.423zm12.154 0H20V6h-1.423zM6.423 6v12z");
}

</style>

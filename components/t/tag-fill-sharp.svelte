<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efdir9bsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tag-fill-sharp" {...props}></Icon>
<style>
:global(.efdir9bsc) {
  fill: currentColor;
  d: path("M12 3c.265 0 .52.105.707.293l8 8a1 1 0 0 1 0 1.414l-8 8a1 1 0 0 1-1.414 0l-8-8A1 1 0 0 1 3 12V4a1 1 0 0 1 1-1ZM7.158 8.221a2 2 0 1 0 3.684 1.558A2 2 0 0 0 7.158 8.22");
}

</style>

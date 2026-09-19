<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="seoivjzwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-screenshot" {...props}></Icon>
<style>
:global(.seoivjzwl) {
  fill: currentColor;
  d: path("M5 1v22h14V1zm12 17H7V6h10zM9.5 8.5H12V7H8v4h1.5zM12 17h4v-4h-1.5v2.5H12z");
}

</style>

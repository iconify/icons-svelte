<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p9w6fklaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:web-asset-20-filled" {...props}></Icon>
<style>
:global(.p9w6fklaj) {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm3.5 0a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="wrncz7bon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:text-bolder-light" {...props}></Icon>
<style>
:global(.wrncz7bon) {
  fill: currentColor;
  d: path("M166.7 116.4A42 42 0 0 0 140 42H64a6.2 6.2 0 0 0-6 6v152a6 6 0 0 0 6 6h88a46 46 0 0 0 14.7-89.6ZM70 54h70a30 30 0 0 1 0 60H70Zm82 140H70v-68h82a34 34 0 0 1 0 68Z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqme15bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-fit-screen" {...props}></Icon>
<style>
:global(.yqme15bzm) {
  fill: currentColor;
  d: path("M17 4h5v5h-2V6h-3zM4 9V6h3V4H2v5zm16 6v3h-3v2h5v-5zM7 18H4v-3H2v5h5zM18 8H6v8h12z");
}

</style>

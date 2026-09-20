<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-yaqpbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:web-outline-sharp" {...props}></Icon>
<style>
:global(.i-yaqpbgi) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h10.5v-3.5H4zm12.5 0H20V9h-3.5zM4 12.5h10.5V9H4z");
}

</style>

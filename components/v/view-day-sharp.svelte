<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ky5zau9vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-day-sharp" {...props}></Icon>
<style>
:global(.ky5zau9vn) {
  fill: currentColor;
  d: path("M3 20v-2h18v2zm0-4V8h18v8zM3 6V4h18v2z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tza20vb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:storage" {...props}></Icon>
<style>
:global(.tza20vb4d) {
  fill: currentColor;
  d: path("M3 20v-4h18v4zm2-1h2v-2H5zM3 8V4h18v4zm2-1h2V5H5zm-2 7v-4h18v4zm2-1h2v-2H5z");
}

</style>

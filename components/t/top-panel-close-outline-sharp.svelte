<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmow40x-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:top-panel-close-outline-sharp" {...props}></Icon>
<style>
:global(.mmow40x-m) {
  fill: currentColor;
  d: path("M8 16.5h8l-4-4zM5 8h14V5H5zm0 11h14v-9H5zM5 8V5zM3 21V3h18v18z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivlbszb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:scrollable-header-outline-sharp" {...props}></Icon>
<style>
:global(.ivlbszb4w) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14v-5H5zm0-7h14V5H5zm0 0V5z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wio8cjbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:tooltip-outline-sharp" {...props}></Icon>
<style>
:global(.wio8cjbji) {
  fill: currentColor;
  d: path("m12 21l-2.29-3.5H3V3h18v14.5h-6.71zm0-1.811l1.754-2.689H20V4H4v12.5h6.246zm0-8.939");
}

</style>

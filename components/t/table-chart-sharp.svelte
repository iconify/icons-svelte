<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2a8yba1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:table-chart-sharp" {...props}></Icon>
<style>
:global(.h2a8yba1e) {
  fill: currentColor;
  d: path("M4 8.5V4h16v4.5zM4 20V9.5h3.885V20zm12.116 0V9.5H20V20zm-7.231 0V9.5h6.23V20z");
}

</style>

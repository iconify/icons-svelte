<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exkmwtb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:transition-chop-sharp" {...props}></Icon>
<style>
:global(.exkmwtb9n) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1.817-1H20V6h-4.844l2.248 8.692z");
}

</style>

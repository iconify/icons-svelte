<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxcaocbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:transition-chop-outline-sharp" {...props}></Icon>
<style>
:global(.kxcaocbcl) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-3.45l11.55-3L13.6 6H4zM6.375 18H20V6h-4.325L18 15zM4 6");
}

</style>

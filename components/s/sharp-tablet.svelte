<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys0xw46sh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-tablet" {...props}></Icon>
<style>
:global(.ys0xw46sh) {
  fill: currentColor;
  d: path("M23 4H1v16h21.99zm-4 14H5V6h14z");
}

</style>

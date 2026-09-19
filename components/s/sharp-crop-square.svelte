<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r75uvjn9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-crop-square" {...props}></Icon>
<style>
:global(.r75uvjn9u) {
  fill: currentColor;
  d: path("M20 4H4v16h16zm-2 14H6V6h12z");
}

</style>

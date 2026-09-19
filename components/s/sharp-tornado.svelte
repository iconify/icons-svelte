<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rftmi0ejo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-tornado" {...props}></Icon>
<style>
:global(.rftmi0ejo) {
  fill: currentColor;
  d: path("M20.11 8L23 3H1l2.89 5zM7.95 15L12 22l4.05-7zm11-5H5.05l1.74 3h10.42z");
}

</style>

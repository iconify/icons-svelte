<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="n_zx_4w6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:wifi-none-thin" {...props}></Icon>
<style>
:global(.n_zx_4w6b) {
  fill: currentColor;
  d: path("M136 204a8 8 0 1 1-8-8a8 8 0 0 1 8 8");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ov7tzybob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:subset-of" {...props}></Icon>
<style>
:global(.ov7tzybob) {
  fill: currentColor;
  d: path("M208 208a8 8 0 0 1-8 8H48a8 8 0 0 1 0-16h152a8 8 0 0 1 8 8m-8-48h-96a48 48 0 0 1 0-96h96a8 8 0 0 0 0-16h-96a64 64 0 0 0 0 128h96a8 8 0 0 0 0-16");
}

</style>

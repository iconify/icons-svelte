<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="k-j886ypt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:shopping-bag-bold" {...props}></Icon>
<style>
:global(.k-j886ypt) {
  fill: currentColor;
  d: path("M216 36H40a20 20 0 0 0-20 20v144a20 20 0 0 0 20 20h176a20 20 0 0 0 20-20V56a20 20 0 0 0-20-20m-4 160H44V60h168ZM76 88a12 12 0 0 1 24 0a28 28 0 0 0 56 0a12 12 0 0 1 24 0a52 52 0 0 1-104 0");
}

</style>

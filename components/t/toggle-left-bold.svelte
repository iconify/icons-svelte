<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="gzihxgbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:toggle-left-bold" {...props}></Icon>
<style>
:global(.gzihxgbte) {
  fill: currentColor;
  d: path("M176 52H80a76 76 0 0 0 0 152h96a76 76 0 0 0 0-152m0 128H80a52 52 0 0 1 0-104h96a52 52 0 0 1 0 104M80 88a40 40 0 1 0 40 40a40 40 0 0 0-40-40m0 56a16 16 0 1 1 16-16a16 16 0 0 1-16 16");
}

</style>

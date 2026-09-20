<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="b8yd2mbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:sidebar-simple-bold" {...props}></Icon>
<style>
:global(.b8yd2mbtc) {
  fill: currentColor;
  d: path("M216 36H40a20 20 0 0 0-20 20v144a20 20 0 0 0 20 20h176a20 20 0 0 0 20-20V56a20 20 0 0 0-20-20M44 60h32v136H44Zm168 136H100V60h112Z");
}

</style>

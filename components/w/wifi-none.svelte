<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="or11-532u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:wifi-none" {...props}></Icon>
<style>
:global(.or11-532u) {
  fill: currentColor;
  d: path("M140 204a12 12 0 1 1-12-12a12 12 0 0 1 12 12");
}

</style>

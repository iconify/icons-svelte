<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="r4mf2qotf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:wifi-low-bold" {...props}></Icon>
<style>
:global(.r4mf2qotf) {
  fill: currentColor;
  d: path("M144 204a16 16 0 1 1-16-16a16 16 0 0 1 16 16m31.06-48.7a80 80 0 0 0-94.12 0a12 12 0 1 0 14.13 19.4a56 56 0 0 1 65.86 0a12 12 0 1 0 14.13-19.4");
}

</style>

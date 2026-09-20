<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mt78cyb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:tag-simple-thin" {...props}></Icon>
<style>
:global(.mt78cyb-z) {
  fill: currentColor;
  d: path("M243.33 125.78L197.7 57.34a12 12 0 0 0-10-5.34H40a12 12 0 0 0-12 12v128a12 12 0 0 0 12 12h147.72a12 12 0 0 0 10-5.34l45.63-68.44a4 4 0 0 0-.02-4.44m-52.28 68.44a4 4 0 0 1-3.33 1.78H40a4 4 0 0 1-4-4V64a4 4 0 0 1 4-4h147.72a4 4 0 0 1 3.33 1.78L235.19 128Z");
}

</style>

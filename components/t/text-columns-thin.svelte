<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="z4l6gx6fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:text-columns-thin" {...props}></Icon>
<style>
:global(.z4l6gx6fp) {
  fill: currentColor;
  d: path("M116 64a4 4 0 0 1-4 4H40a4 4 0 0 1 0-8h72a4 4 0 0 1 4 4m-4 36H40a4 4 0 0 0 0 8h72a4 4 0 0 0 0-8m0 40H40a4 4 0 0 0 0 8h72a4 4 0 0 0 0-8m0 40H40a4 4 0 0 0 0 8h72a4 4 0 0 0 0-8m32-112h72a4 4 0 0 0 0-8h-72a4 4 0 0 0 0 8m72 32h-72a4 4 0 0 0 0 8h72a4 4 0 0 0 0-8m0 40h-72a4 4 0 0 0 0 8h72a4 4 0 0 0 0-8m0 40h-72a4 4 0 0 0 0 8h72a4 4 0 0 0 0-8");
}

</style>

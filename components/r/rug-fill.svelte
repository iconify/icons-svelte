<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="uaszzcp9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:rug-fill" {...props}></Icon>
<style>
:global(.uaszzcp9o) {
  fill: currentColor;
  d: path("M200 16a8 8 0 0 0-8 8v16h-32V24a8 8 0 0 0-16 0v16h-32V24a8 8 0 0 0-16 0v16H64V24a8 8 0 0 0-16 0v208a8 8 0 0 0 16 0v-16h32v16a8 8 0 0 0 16 0v-16h32v16a8 8 0 0 0 16 0v-16h32v16a8 8 0 0 0 16 0V24a8 8 0 0 0-8-8m-44.57 114.06l-24 40a4 4 0 0 1-6.86 0l-24-40a4 4 0 0 1 0-4.12l24-40a4 4 0 0 1 6.86 0l24 40a4 4 0 0 1 0 4.12");
}

</style>

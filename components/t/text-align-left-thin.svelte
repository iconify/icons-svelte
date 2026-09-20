<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="kh-0q0pvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:text-align-left-thin" {...props}></Icon>
<style>
:global(.kh-0q0pvy) {
  fill: currentColor;
  d: path("M36 64a4 4 0 0 1 4-4h176a4 4 0 0 1 0 8H40a4 4 0 0 1-4-4m4 44h128a4 4 0 0 0 0-8H40a4 4 0 0 0 0 8m176 32H40a4 4 0 0 0 0 8h176a4 4 0 0 0 0-8m-48 40H40a4 4 0 0 0 0 8h128a4 4 0 0 0 0-8");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x9n1jpjgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:toggle-right-20-regular" {...props}></Icon>
<style>
:global(.x9n1jpjgu) {
  fill: currentColor;
  d: path("M14 12a2 2 0 1 0 0-4a2 2 0 0 0 0 4M2 10a4 4 0 0 1 4-4h8a4 4 0 0 1 0 8H6a4 4 0 0 1-4-4m4-3a3 3 0 0 0 0 6h8a3 3 0 1 0 0-6z");
}

</style>

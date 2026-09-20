<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="veluvebuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:toggle-left-20-regular" {...props}></Icon>
<style>
:global(.veluvebuc) {
  fill: currentColor;
  d: path("M6 12a2 2 0 1 1 0-4a2 2 0 0 1 0 4m12-2a4 4 0 0 0-4-4H6a4 4 0 1 0 0 8h8a4 4 0 0 0 4-4m-4-3a3 3 0 1 1 0 6H6a3 3 0 1 1 0-6z");
}

</style>

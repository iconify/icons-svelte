<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zrokgqbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:toggle-right-20-filled" {...props}></Icon>
<style>
:global(.zrokgqbld) {
  fill: currentColor;
  d: path("M6 6a4 4 0 1 0 0 8h8a4 4 0 0 0 0-8zm8 6a2 2 0 1 1 0-4a2 2 0 0 1 0 4");
}

</style>

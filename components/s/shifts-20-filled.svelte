<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gq6ny6bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:shifts-20-filled" {...props}></Icon>
<style>
:global(.gq6ny6bex) {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm7 .5a.5.5 0 0 0-1 0v4a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 0-1H10z");
}

</style>

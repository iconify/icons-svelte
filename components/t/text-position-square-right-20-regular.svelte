<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l3-dl9b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-position-square-right-20-regular" {...props}></Icon>
<style>
:global(.l3-dl9b5k) {
  fill: currentColor;
  d: path("M16.5 3a.5.5 0 0 1 0 1h-13a.5.5 0 0 1 0-1zM8 6a.5.5 0 0 1 0 1H3.5a.5.5 0 0 1 0-1zm.5 3.5A.5.5 0 0 0 8 9H3.5a.5.5 0 0 0 0 1H8a.5.5 0 0 0 .5-.5M8 12a.5.5 0 0 1 0 1H3.5a.5.5 0 0 1 0-1zm9 3.5a.5.5 0 0 0-.5-.5h-13a.5.5 0 0 0 0 1h13a.5.5 0 0 0 .5-.5m-1-7a2.5 2.5 0 0 0-5 0v5a.5.5 0 0 1-1 0v-5a3.5 3.5 0 1 1 7 0v5a.5.5 0 0 1-1 0z");
}

</style>

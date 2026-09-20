<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o1krpdb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-column-one-narrow-20-filled" {...props}></Icon>
<style>
:global(.o1krpdb5b) {
  fill: currentColor;
  d: path("M7.75 5a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5zm0 3a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5zM7 11.75a.75.75 0 0 1 .75-.75h4.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1-.75-.75M7.75 14a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5z");
}

</style>

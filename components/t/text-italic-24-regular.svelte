<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kktk8-76i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-italic-24-regular" {...props}></Icon>
<style>
:global(.kktk8-76i) {
  fill: currentColor;
  d: path("M18.75 4a.75.75 0 0 1 0 1.5h-3.482l-4.932 13h3.414a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5h3.482l4.932-13H10.25a.75.75 0 0 1 0-1.5z");
}

</style>

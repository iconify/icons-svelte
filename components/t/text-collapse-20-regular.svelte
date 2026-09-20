<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rmr85fw4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-collapse-20-regular" {...props}></Icon>
<style>
:global(.rmr85fw4z) {
  fill: currentColor;
  d: path("M5 3.5a.5.5 0 0 1 .5-.5h12a.5.5 0 0 1 0 1h-12a.5.5 0 0 1-.5-.5m0 12a.5.5 0 0 1 .5-.5h12a.5.5 0 0 1 0 1h-12a.5.5 0 0 1-.5-.5m6-8a.5.5 0 0 1 .5-.5h6a.5.5 0 0 1 0 1h-6a.5.5 0 0 1-.5-.5m0 4a.5.5 0 0 1 .5-.5h6a.5.5 0 0 1 0 1h-6a.5.5 0 0 1-.5-.5m-2-2a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0M3.5 9a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1z");
}

</style>

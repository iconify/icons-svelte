<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lu8tfbe7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-justify-low-20-regular" {...props}></Icon>
<style>
:global(.lu8tfbe7s) {
  fill: currentColor;
  d: path("M9 4.5a.5.5 0 0 1 .5-.5h8a.5.5 0 0 1 0 1h-8a.5.5 0 0 1-.5-.5m0 5a.5.5 0 0 1 .5-.5h8a.5.5 0 0 1 0 1h-8a.5.5 0 0 1-.5-.5M2.5 14a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1z");
}

</style>

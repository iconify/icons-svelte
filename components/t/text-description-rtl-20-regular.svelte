<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tnyr5tble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-description-rtl-20-regular" {...props}></Icon>
<style>
:global(.tnyr5tble) {
  fill: currentColor;
  d: path("M17.5 5a.5.5 0 0 1 0 1h-15a.5.5 0 0 1 0-1zm0 3a.5.5 0 0 1 0 1h-15a.5.5 0 0 1 0-1zm.5 3.5a.5.5 0 0 0-.5-.5h-15a.5.5 0 0 0 0 1h15a.5.5 0 0 0 .5-.5m-.5 2.5a.5.5 0 0 1 0 1h-10a.5.5 0 0 1 0-1z");
}

</style>

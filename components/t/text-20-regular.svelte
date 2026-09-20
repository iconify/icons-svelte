<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m3wh9rs9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-20-regular" {...props}></Icon>
<style>
:global(.m3wh9rs9d) {
  fill: currentColor;
  d: path("M4 3.5a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0V4h-4v12h1.5a.5.5 0 0 1 0 1h-4a.5.5 0 0 1 0-1H9V4H5v1.5a.5.5 0 0 1-1 0z");
}

</style>

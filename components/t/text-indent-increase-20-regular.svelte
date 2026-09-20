<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mwsh-u93l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-indent-increase-20-regular" {...props}></Icon>
<style>
:global(.mwsh-u93l) {
  fill: currentColor;
  d: path("M6 4.5a.5.5 0 0 1 .5-.5h8a.5.5 0 0 1 0 1h-8a.5.5 0 0 1-.5-.5m0 5a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5m.5 4.5a.5.5 0 0 0 0 1h6a.5.5 0 0 0 0-1zM2.854 7.732a.5.5 0 1 0-.708.707L3.207 9.5l-1.06 1.06a.5.5 0 1 0 .707.708l1.414-1.414a.5.5 0 0 0 0-.708z");
}

</style>

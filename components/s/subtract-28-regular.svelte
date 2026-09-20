<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="t8z5zwmqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:subtract-28-regular" {...props}></Icon>
<style>
:global(.t8z5zwmqr) {
  fill: currentColor;
  d: path("M3 13.75a.75.75 0 0 1 .75-.75h20.5a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1-.75-.75");
}

</style>

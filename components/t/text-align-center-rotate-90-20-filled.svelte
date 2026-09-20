<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p7norhswx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-center-rotate-90-20-filled" {...props}></Icon>
<style>
:global(.p7norhswx) {
  fill: currentColor;
  d: path("M15.75 4a.75.75 0 0 1 .75.75v10.5a.75.75 0 0 1-1.5 0V4.75a.75.75 0 0 1 .75-.75m-5-2a.75.75 0 0 1 .75.75v14.5a.75.75 0 0 1-1.5 0V2.75a.75.75 0 0 1 .75-.75M6.5 6.75a.75.75 0 0 0-1.5 0v6.5a.75.75 0 0 0 1.5 0z");
}

</style>

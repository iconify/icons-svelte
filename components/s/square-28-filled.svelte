<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="j3gx1gbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:square-28-filled" {...props}></Icon>
<style>
:global(.j3gx1gbhb) {
  fill: currentColor;
  d: path("M3 6.75A3.75 3.75 0 0 1 6.75 3h14.5A3.75 3.75 0 0 1 25 6.75v14.5A3.75 3.75 0 0 1 21.25 25H6.75A3.75 3.75 0 0 1 3 21.25z");
}

</style>

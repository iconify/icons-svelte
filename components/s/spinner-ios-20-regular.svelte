<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tac85ch4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:spinner-ios-20-regular" {...props}></Icon>
<style>
:global(.tac85ch4e) {
  fill: currentColor;
  d: path("M10 3a7 7 0 0 0-7 7a.5.5 0 0 1-1 0a8 8 0 1 1 8 8a.5.5 0 0 1 0-1a7 7 0 1 0 0-14");
}

</style>

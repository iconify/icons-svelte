<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xd5f54bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:spacebar-20-filled" {...props}></Icon>
<style>
:global(.xd5f54bxv) {
  fill: currentColor;
  d: path("M2.75 7.75a.75.75 0 0 1 .75.75v2h13v-2a.75.75 0 0 1 1.5 0v2a1.5 1.5 0 0 1-1.5 1.5h-13A1.5 1.5 0 0 1 2 10.5v-2a.75.75 0 0 1 .75-.75");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hfuaovbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:triangle-left-12-filled" {...props}></Icon>
<style>
:global(.hfuaovbuu) {
  fill: currentColor;
  d: path("M1.459 5.214a.903.903 0 0 0 0 1.572l7.169 4.092c.61.348 1.372-.089 1.372-.787V1.91c0-.698-.762-1.135-1.372-.787z");
}

</style>

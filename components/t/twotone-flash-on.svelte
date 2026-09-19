<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ou4baab9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-flash-on" {...props}></Icon>
<style>
:global(.ou4baab9p) {
  fill: currentColor;
  d: path("M17 10h-4l3-8H7v11h3v9z");
}

</style>

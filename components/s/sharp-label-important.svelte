<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb1oopb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-label-important" {...props}></Icon>
<style>
:global(.zb1oopb0n) {
  fill: currentColor;
  d: path("M4 18.99h12.04L21 12l-4.97-7H4l5 7z");
}

</style>

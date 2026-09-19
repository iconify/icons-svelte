<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilhqy3baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-pan-tool-alt" {...props}></Icon>
<style>
:global(.ilhqy3baw) {
  fill: currentColor;
  d: path("M20.18 13.4L19.1 21h-9L5 15.62l1.22-1.23l3.78.85V4.5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5v6h1.38z");
}

</style>

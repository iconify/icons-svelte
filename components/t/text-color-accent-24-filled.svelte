<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrv6qx89k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-color-accent-24-filled" {...props}></Icon>
<style>
:global(.nrv6qx89k) {
  fill: currentColor;
  d: path("M18.75 15.75a1.5 1.5 0 0 1 1.5 1.5v2.5a1.5 1.5 0 0 1-1.5 1.5H5.25a1.5 1.5 0 0 1-1.5-1.5v-2.5a1.5 1.5 0 0 1 1.5-1.5z");
}

</style>

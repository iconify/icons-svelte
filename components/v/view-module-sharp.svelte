<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xafz3uw9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-module-sharp" {...props}></Icon>
<style>
:global(.xafz3uw9j) {
  fill: currentColor;
  d: path("M15.675 11.5V5H21v6.5zm-6.325 0V5h5.325v6.5zm-6.325 0V5H8.35v6.5zm0 7.5v-6.5H8.35V19zm6.325 0v-6.5h5.325V19zm6.325 0v-6.5H21V19z");
}

</style>

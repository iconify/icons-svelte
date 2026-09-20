<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozhad2bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-center-24-filled" {...props}></Icon>
<style>
:global(.ozhad2bmy) {
  fill: currentColor;
  d: path("M4 6a1 1 0 0 1 1-1h14a1 1 0 1 1 0 2H5a1 1 0 0 1-1-1m2 12a1 1 0 0 1 1-1h10a1 1 0 1 1 0 2H7a1 1 0 0 1-1-1m-3-7a1 1 0 1 0 0 2h18a1 1 0 1 0 0-2z");
}

</style>

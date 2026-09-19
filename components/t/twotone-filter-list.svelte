<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pffl33b1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-filter-list" {...props}></Icon>
<style>
:global(.pffl33b1v) {
  fill: currentColor;
  d: path("M10 18h4v-2h-4zM3 6v2h18V6zm3 7h12v-2H6z");
}

</style>

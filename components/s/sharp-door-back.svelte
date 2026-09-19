<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiu1upb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-door-back" {...props}></Icon>
<style>
:global(.jiu1upb9y) {
  fill: currentColor;
  d: path("M19 19V3H5v16H3v2h18v-2zm-8-6H9v-2h2z");
}

</style>

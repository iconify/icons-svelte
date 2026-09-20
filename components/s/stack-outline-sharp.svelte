<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7m0w4v1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stack-outline-sharp" {...props}></Icon>
<style>
:global(.y7m0w4v1y) {
  fill: currentColor;
  d: path("M6.616 14v1H3V3h12v3.616h-1V4H4v10zM9 21V9h12v12zm1-1h10V10H10zm5-5");
}

</style>

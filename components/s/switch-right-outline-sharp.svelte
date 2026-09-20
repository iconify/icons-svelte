<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rclmj10lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:switch-right-outline-sharp" {...props}></Icon>
<style>
:global(.rclmj10lx) {
  fill: currentColor;
  d: path("m10 19l-7-7l7-7zm4 0V5l7 7zm1.5-3.625L18.875 12L15.5 8.625z");
}

</style>

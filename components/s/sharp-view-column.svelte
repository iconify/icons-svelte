<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi6f_gb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-view-column" {...props}></Icon>
<style>
:global(.mi6f_gb_b) {
  fill: currentColor;
  d: path("M14.67 5v14H9.33V5zm1 14H21V5h-5.33zm-7.34 0V5H3v14z");
}

</style>

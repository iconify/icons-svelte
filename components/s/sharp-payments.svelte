<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxdivibzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-payments" {...props}></Icon>
<style>
:global(.nxdivibzu) {
  fill: currentColor;
  d: path("M23 7v13H4v-2h17V7zm-4 9H1V4h18zm-6-6c0-1.66-1.34-3-3-3s-3 1.34-3 3s1.34 3 3 3s3-1.34 3-3");
}

</style>

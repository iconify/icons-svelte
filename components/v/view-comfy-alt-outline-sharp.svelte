<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyecw4bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:view-comfy-alt-outline-sharp" {...props}></Icon>
<style>
:global(.iyecw4bpx) {
  fill: currentColor;
  d: path("M3 10V3h7v7zm1-1h5V4H4zM3 21v-7h7v7zm1-1h5v-5H4zm10-10V3h7v7zm1-1h5V4h-5zm-1 12v-7h7v7zm1-1h5v-5h-5zm0-5");
}

</style>

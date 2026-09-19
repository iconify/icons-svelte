<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_0xr7bkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-web-asset" {...props}></Icon>
<style>
:global(.a_0xr7bkz) {
  fill: currentColor;
  d: path("M3 4v16h18V4zm16 14H5V8h14z");
}

</style>

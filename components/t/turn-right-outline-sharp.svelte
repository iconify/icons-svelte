<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n94neebvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:turn-right-outline-sharp" {...props}></Icon>
<style>
:global(.n94neebvb) {
  fill: currentColor;
  d: path("M7 20V9h10.2l-1.6-1.6L17 6l4 4l-4 4l-1.4-1.4l1.6-1.6H9v9z");
}

</style>

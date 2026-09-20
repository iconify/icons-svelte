<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f42wdzbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:signal-cellular-connected-no-internet-4-bar-outline-sharp" {...props}></Icon>
<style>
:global(.f42wdzbpu) {
  fill: currentColor;
  d: path("M3 21L21 3v4.23h-3.384V21zm17-3.23V9.615h1v8.153zm-.23 3.46v-1.46h1.46v1.46z");
}

</style>

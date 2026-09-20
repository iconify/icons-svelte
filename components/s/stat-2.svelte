<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwmkc2zcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stat-2" {...props}></Icon>
<style>
:global(.qwmkc2zcp) {
  fill: currentColor;
  d: path("M7.4 17.708L6.692 17L12 11.692L17.308 17l-.708.708l-4.6-4.594zm0-6L6.692 11L12 5.692L17.308 11l-.708.708L12 7.114z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rljjxfb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:window-closed" {...props}></Icon>
<style>
:global(.rljjxfb_h) {
  fill: currentColor;
  d: path("M5 20V4h14v16zm1.77-8.5h4.46v-.77h1.54v.77h4.46V5.77H6.77zm0 6.73h10.46V12.5H6.77zM6 19h12V5H6z");
}

</style>

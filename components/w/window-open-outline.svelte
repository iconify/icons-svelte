<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zicfl3b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:window-open-outline" {...props}></Icon>
<style>
:global(.zicfl3b7h) {
  fill: currentColor;
  d: path("M5 20V4h14v16zm1-8.5h5.23v-.77h1.54v.77H18V5H6zM6 19h12z");
}

</style>

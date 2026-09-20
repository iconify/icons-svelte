<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly--ymb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:window-closed-outline-sharp" {...props}></Icon>
<style>
:global(.ly--ymb3a) {
  fill: currentColor;
  d: path("M5 20V4h14v16zm1-8.5h5.23v-.77h1.54v.77H18V5H6zM6 19h12v-6.5H6zm0 0h12z");
}

</style>

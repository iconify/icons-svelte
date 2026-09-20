<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g26-ovbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:text-ad-sharp" {...props}></Icon>
<style>
:global(.g26-ovbcj) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm2.73-3.116h12.54v-1H5.73zm0-3.384h12.54v-1H5.73zm0-3.384h8.77v-1H5.73z");
}

</style>

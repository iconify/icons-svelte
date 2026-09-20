<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idkrp03-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:width-normal-sharp" {...props}></Icon>
<style>
:global(.idkrp03-j) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h5V6H4zm11 0h5V6h-5z");
}

</style>

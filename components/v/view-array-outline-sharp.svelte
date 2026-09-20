<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iptlssi9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-array-outline-sharp" {...props}></Icon>
<style>
:global(.iptlssi9r) {
  fill: currentColor;
  d: path("M3 19V5h3v14zm4 0V5h10v14zm11 0V5h3v14zm-9-2h6V7H9zm3-5");
}

</style>

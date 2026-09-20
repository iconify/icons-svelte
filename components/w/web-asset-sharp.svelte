<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc2312bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:web-asset-sharp" {...props}></Icon>
<style>
:global(.oc2312bsd) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h16V8H4z");
}

</style>

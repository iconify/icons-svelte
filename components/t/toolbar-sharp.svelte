<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh5k6c_dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:toolbar-sharp" {...props}></Icon>
<style>
:global(.vh5k6c_dg) {
  fill: currentColor;
  d: path("M3 8V3h18v5zm0 13V10h18v11z");
}

</style>

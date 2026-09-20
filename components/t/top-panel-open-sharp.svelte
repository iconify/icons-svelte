<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixncu1bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:top-panel-open-sharp" {...props}></Icon>
<style>
:global(.ixncu1bfg) {
  fill: currentColor;
  d: path("m12 15.596l3.173-3.192H8.827zM5 19h14V9H5zm-1 1V4h16v16z");
}

</style>

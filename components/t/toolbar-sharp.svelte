<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9avs0ujt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:toolbar-sharp" {...props}></Icon>
<style>
:global(.n9avs0ujt) {
  fill: currentColor;
  d: path("M4 8V4h16v4zm0 12V9h16v11z");
}

</style>

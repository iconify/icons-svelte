<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9dz09yvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:split-scene-right-outline-sharp" {...props}></Icon>
<style>
:global(.u9dz09yvh) {
  fill: currentColor;
  d: path("M3 20V4h6v2H5v12h4v2zm8 2V2h2v2h8v16h-8v2zm-6-4V6z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thrpz258i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stairs-2-outline-sharp" {...props}></Icon>
<style>
:global(.thrpz258i) {
  fill: currentColor;
  d: path("M3 18v-1h5.664v-5.5h5.663V6H21v1h-5.663v5.5H9.673V18z");
}

</style>

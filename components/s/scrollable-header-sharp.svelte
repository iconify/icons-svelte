<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu36vqbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:scrollable-header-sharp" {...props}></Icon>
<style>
:global(.vu36vqbxp) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14v-5H5z");
}

</style>

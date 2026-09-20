<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4ggz9b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tab-sharp" {...props}></Icon>
<style>
:global(.y4ggz9b8w) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm11-10h7V6h-7z");
}

</style>

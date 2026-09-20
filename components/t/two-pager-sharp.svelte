<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcr7bgbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:two-pager-sharp" {...props}></Icon>
<style>
:global(.bcr7bgbkq) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm11-2h7V6h-7zm-8-2h5v-2H5zm0-3h5v-2H5zm0-3h5V8H5zm9 6h5v-2h-5zm0-3h5v-2h-5zm0-3h5V8h-5z");
}

</style>

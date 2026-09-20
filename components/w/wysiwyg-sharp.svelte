<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxws4cbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:wysiwyg-sharp" {...props}></Icon>
<style>
:global(.mxws4cbwl) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V7H5zm2-7v-2h10v2zm0 4v-2h6v2z");
}

</style>

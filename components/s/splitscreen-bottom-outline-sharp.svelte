<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykz5wobtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:splitscreen-bottom-outline-sharp" {...props}></Icon>
<style>
:global(.ykz5wobtd) {
  fill: currentColor;
  d: path("M4 19.385v-6h16v6zm0-8.77v-6h16v6zm15-5H5v4h14z");
}

</style>

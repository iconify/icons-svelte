<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh8ggqb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tabs-outline-sharp" {...props}></Icon>
<style>
:global(.bh8ggqb1s) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14v-7H5zm0-9h14V5H5zm7-2h6V6h-6zm-7 2V5z");
}

</style>

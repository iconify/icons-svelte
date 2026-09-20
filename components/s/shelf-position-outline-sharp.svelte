<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtnpfrbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:shelf-position-outline-sharp" {...props}></Icon>
<style>
:global(.qtnpfrbcs) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14v-3H5zm11.5-5H19V5h-2.5zM5 14h2.5V5H5zm4.5 0h5V5h-5z");
}

</style>

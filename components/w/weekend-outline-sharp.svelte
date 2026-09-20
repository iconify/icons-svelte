<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trb6cqboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:weekend-outline-sharp" {...props}></Icon>
<style>
:global(.trb6cqboq) {
  fill: currentColor;
  d: path("M1 20V9h3V4h16v5h3v11zm6-6h10V9h1V6H6v3h1zm-4 4h18v-7h-2v5H5v-5H3zm9-2");
}

</style>

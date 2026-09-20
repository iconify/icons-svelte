<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z28tpzb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:team-dashboard-outline-sharp" {...props}></Icon>
<style>
:global(.z28tpzb4d) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm7-2v-6H5v6zm2 0h7v-6h-7zm-7-8h14V5H5z");
}

</style>

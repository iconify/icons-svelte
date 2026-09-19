<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6rivubjr"/><path class="ephfub3ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-shop-2" {...props}></Icon>
<style>
:global(.ephfub3ut) {
  fill: currentColor;
  d: path("M18 5V1h-8v4H5v13h18V5zm-6-2h4v2h-4zm0 12V8l5.5 3.5z");
}

:global(.i6rivubjr) {
  fill: currentColor;
  d: path("M3 9H1v13h18v-2H3z");
}

</style>

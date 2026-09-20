<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr9gnfb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:web-asset-sharp" {...props}></Icon>
<style>
:global(.gr9gnfb0h) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h16V8H4z");
}

</style>

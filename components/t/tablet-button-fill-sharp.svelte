<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjmwf8blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tablet-button-fill-sharp" {...props}></Icon>
<style>
:global(.vjmwf8blc) {
  fill: currentColor;
  d: path("M3 21V3a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1m9.01-4H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>

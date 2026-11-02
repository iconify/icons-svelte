<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0yu7z-4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-align-justify-bulk" {...props}></Icon>
<style>
:global(.o0yu7z-4s) {
  fill: currentColor;
  d: path("M20 5a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Z");
}

</style>

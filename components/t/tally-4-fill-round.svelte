<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzem-_fgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tally-4-fill-round" {...props}></Icon>
<style>
:global(.lzem-_fgn) {
  fill: currentColor;
  d: path("M7 19a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Z");
}

</style>

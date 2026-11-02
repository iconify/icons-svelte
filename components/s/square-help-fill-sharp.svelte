<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1showb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-help-fill-sharp" {...props}></Icon>
<style>
:global(.n1showb-n) {
  fill: currentColor;
  d: path("M2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m6-10a1 1 0 0 0 2 0a2 2 0 1 1 2 2a1 1 0 0 0 0 2a4 4 0 1 0-4-4m4 5a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>

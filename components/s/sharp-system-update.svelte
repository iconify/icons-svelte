<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q59alokok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-system-update" {...props}></Icon>
<style>
:global(.q59alokok) {
  fill: currentColor;
  d: path("M5 1v22h14V1zm12 18H7V5h10zm-1-6h-3V8h-2v5H8l4 4z");
}

</style>

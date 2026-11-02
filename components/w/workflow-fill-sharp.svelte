<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pftyt_bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:workflow-fill-sharp" {...props}></Icon>
<style>
:global(.pftyt_bzi) {
  fill: currentColor;
  d: path("M11 2a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H8v4h4v-3a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-8a1 1 0 0 1-1-1v-3H7a1 1 0 0 1-1-1v-5H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elx_9_pak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:split-scene-down-outline-sharp" {...props}></Icon>
<style>
:global(.elx_9_pak) {
  fill: currentColor;
  d: path("M4 9V3h16v6h-2V5H6v4zm0 12v-8H2v-2h20v2h-2v8zM6 5h12z");
}

</style>

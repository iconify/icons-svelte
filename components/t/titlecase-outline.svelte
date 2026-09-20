<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkljx6mtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:titlecase-outline" {...props}></Icon>
<style>
:global(.mkljx6mtz) {
  fill: currentColor;
  d: path("M8.966 17.173V8.331H5.985v-.946h6.93v.946h-2.96v8.842zm8.33.23q-.888 0-1.475-.598q-.586-.6-.586-1.494v-3.953h-1.35v-.873h1.35V8.31h.919v2.174h1.85v.874h-1.85v3.815q0 .575.349.958t.857.383q.15 0 .31-.03q.159-.03.346-.103v.91q-.193.07-.368.092q-.175.02-.352.02");
}

</style>

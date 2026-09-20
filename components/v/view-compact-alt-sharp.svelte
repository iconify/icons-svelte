<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8c7ymbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:view-compact-alt-sharp" {...props}></Icon>
<style>
:global(.n8c7ymbes) {
  fill: currentColor;
  d: path("M8.25 15.75h3v-3h-3zm0-4.5h3v-3h-3zm4.5 4.5h3v-3h-3zm0-4.5h3v-3h-3zM3 19V5h18v14z");
}

</style>

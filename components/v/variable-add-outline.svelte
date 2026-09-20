<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmfk4ybyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:variable-add-outline" {...props}></Icon>
<style>
:global(.cmfk4ybyx) {
  fill: currentColor;
  d: path("M14 17H3V7h18v3h-2V9H5v6h9zm-9-2V9zm14 5v-3h-3v-2h3v-3h2v3h3v2h-3v3z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnc0zpvjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stat-0-outline-sharp" {...props}></Icon>
<style>
:global(.pnc0zpvjb) {
  fill: currentColor;
  d: path("m12 19l-7-7l7-7l7 7zm0-2.85L16.15 12L12 7.85L7.85 12zM12 12");
}

</style>

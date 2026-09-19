<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxndxzbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-bed" {...props}></Icon>
<style>
:global(.sxndxzbac) {
  fill: currentColor;
  d: path("M21 10V5H3v5H2v9h2v-2h16v2h2v-9zm-8-3h6v3h-6zm-8 3V7h6v3zm-1 5v-3h16v3z");
}

</style>

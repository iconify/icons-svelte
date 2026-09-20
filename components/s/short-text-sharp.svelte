<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxt89abcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:short-text-sharp" {...props}></Icon>
<style>
:global(.oxt89abcn) {
  fill: currentColor;
  d: path("M4 15v-2h10v2zm0-4V9h16v2z");
}

</style>

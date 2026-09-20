<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u63g9u3in"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:shift-lock" {...props}></Icon>
<style>
:global(.u63g9u3in) {
  fill: currentColor;
  d: path("M8 18v-5H3l9-11l9 11h-5v5zm-4 4v-2h16v2z");
}

</style>

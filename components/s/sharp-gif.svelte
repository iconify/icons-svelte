<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s083s7bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-gif" {...props}></Icon>
<style>
:global(.s083s7bdr) {
  fill: currentColor;
  d: path("M11.5 9H13v6h-1.5zM10 9H5v6h5v-3H8.5v1.5h-2v-3H10zm9 1.5V9h-4.5v6H16v-2h2v-1.5h-2v-1z");
}

</style>

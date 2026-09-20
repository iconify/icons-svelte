<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5nv9x7ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:valve-sharp" {...props}></Icon>
<style>
:global(.g5nv9x7ap) {
  fill: currentColor;
  d: path("M11 8V5H7V3h10v2h-4v3zM4 21v-8h2v1h3v-3H8V9h8v2h-1v3h3v-1h2v8h-2v-1H6v1z");
}

</style>

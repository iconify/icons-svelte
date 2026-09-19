<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s_or9zcmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:satori-reader" {...props}></Icon>
<style>
:global(.s_or9zcmo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.295 42.5L40.79 16.538l-4.354-5.389l4.664-1.4l-10-4.249l-3.886 8.188L6.9 24h18.292z");
}

</style>

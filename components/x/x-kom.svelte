<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zayi60b6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:x-kom" {...props}></Icon>
<style>
:global(.zayi60b6x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.51 24l13.056-13.055a3.188 3.188 0 1 0-4.51-4.51L24 19.49L10.945 6.435a3.188 3.188 0 1 0-4.51 4.51L19.49 24L6.434 37.055a3.188 3.188 0 1 0 4.51 4.51L24 28.512l13.055 13.055c.623.623 1.44.934 2.255.934s1.633-.311 2.256-.934a3.19 3.19 0 0 0 0-4.51z");
}

</style>

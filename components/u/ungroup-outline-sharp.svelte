<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj7albbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:ungroup-outline-sharp" {...props}></Icon>
<style>
:global(.pj7albbci) {
  fill: currentColor;
  d: path("m8.7 15.989l-.688-.689l4.8-4.8H8.5v-1h6v6h-1v-4.311zM19 12V5h-7V4h8v8zM4 20V4h1v15h15v1z");
}

</style>

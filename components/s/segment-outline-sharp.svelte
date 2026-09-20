<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gd479hbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:segment-outline-sharp" {...props}></Icon>
<style>
:global(.gd479hbkb) {
  fill: currentColor;
  d: path("M9 18v-2h12v2zm0-5v-2h12v2zM3 8V6h18v2z");
}

</style>

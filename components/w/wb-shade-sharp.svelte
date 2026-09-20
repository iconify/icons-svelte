<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7-ympr0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:wb-shade-sharp" {...props}></Icon>
<style>
:global(.i7-ympr0s) {
  fill: currentColor;
  d: path("M19.5 20L14 14.5V12l8 8zM14 20v-3l3 3zM4 20V10H2l6-6l6 6h-2v10zm3-6h2v-4H7z");
}

</style>

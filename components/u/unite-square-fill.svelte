<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="paq2a2b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:unite-square-fill" {...props}></Icon>
<style>
:global(.paq2a2b5c) {
  fill: currentColor;
  d: path("M224 96v120a8 8 0 0 1-8 8H96a8 8 0 0 1-8-8v-48H40a8 8 0 0 1-8-8V40a8 8 0 0 1 8-8h120a8 8 0 0 1 8 8v48h48a8 8 0 0 1 8 8");
}

</style>

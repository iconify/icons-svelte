<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="u4cplnbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:square-logo-bold" {...props}></Icon>
<style>
:global(.u4cplnbmu) {
  fill: currentColor;
  d: path("M208 28H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-4 176H52V52h152ZM96 172h64a12 12 0 0 0 12-12V96a12 12 0 0 0-12-12H96a12 12 0 0 0-12 12v64a12 12 0 0 0 12 12m12-64h40v40h-40Z");
}

</style>

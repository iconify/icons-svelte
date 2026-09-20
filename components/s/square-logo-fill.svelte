<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="emr2ekbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:square-logo-fill" {...props}></Icon>
<style>
:global(.emr2ekbrp) {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m0 176H48V48h160zM168 96v64a8 8 0 0 1-8 8H96a8 8 0 0 1-8-8V96a8 8 0 0 1 8-8h64a8 8 0 0 1 8 8");
}

</style>

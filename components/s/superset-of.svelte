<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="dm_288bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:superset-of" {...props}></Icon>
<style>
:global(.dm_288bdf) {
  fill: currentColor;
  d: path("M216 200a8 8 0 0 1-8 8H56a8 8 0 0 1 0-16h152a8 8 0 0 1 8 8m-64-48H56a8 8 0 0 0 0 16h96a64 64 0 0 0 0-128H56a8 8 0 0 0 0 16h96a48 48 0 0 1 0 96");
}

</style>

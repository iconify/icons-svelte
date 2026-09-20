<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="h7g_ojahb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:superset-of-thin" {...props}></Icon>
<style>
:global(.h7g_ojahb) {
  fill: currentColor;
  d: path("M212 200a4 4 0 0 1-4 4H56a4 4 0 0 1 0-8h152a4 4 0 0 1 4 4m-60-44H56a4 4 0 0 0 0 8h96a60 60 0 0 0 0-120H56a4 4 0 0 0 0 8h96a52 52 0 0 1 0 104");
}

</style>

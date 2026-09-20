<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="nxck4tfas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:sliders-horizontal-thin" {...props}></Icon>
<style>
:global(.nxck4tfas) {
  fill: currentColor;
  d: path("M40 84h36.29a28 28 0 0 0 55.42 0H216a4 4 0 0 0 0-8h-84.29a28 28 0 0 0-55.42 0H40a4 4 0 0 0 0 8m64-24a20 20 0 1 1-20 20a20 20 0 0 1 20-20m112 112h-20.29a28 28 0 0 0-55.42 0H40a4 4 0 0 0 0 8h100.29a28 28 0 0 0 55.42 0H216a4 4 0 0 0 0-8m-48 24a20 20 0 1 1 20-20a20 20 0 0 1-20 20");
}

</style>

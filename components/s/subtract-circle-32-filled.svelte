<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c1u6we7lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:subtract-circle-32-filled" {...props}></Icon>
<style>
:global(.c1u6we7lx) {
  fill: currentColor;
  d: path("M30 16c0 7.732-6.268 14-14 14S2 23.732 2 16S8.268 2 16 2s14 6.268 14 14m-20-1a1 1 0 1 0 0 2h12a1 1 0 1 0 0-2z");
}

</style>

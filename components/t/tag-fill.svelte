<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="yb1shqboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:tag-fill" {...props}></Icon>
<style>
:global(.yb1shqboz) {
  fill: currentColor;
  d: path("M243.31 136L144 36.69A15.86 15.86 0 0 0 132.69 32H40a8 8 0 0 0-8 8v92.69A15.86 15.86 0 0 0 36.69 144L136 243.31a16 16 0 0 0 22.63 0l84.68-84.68a16 16 0 0 0 0-22.63M84 96a12 12 0 1 1 12-12a12 12 0 0 1-12 12");
}

</style>

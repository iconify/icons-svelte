<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i9utorbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-16-regular" {...props}></Icon>
<style>
:global(.i9utorbmg) {
  fill: currentColor;
  d: path("M3 2.5a.5.5 0 0 1 .5-.5h8a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0V3H8v10h1a.5.5 0 0 1 0 1H6a.5.5 0 0 1 0-1h1V3H4v1.5a.5.5 0 0 1-1 0z");
}

</style>

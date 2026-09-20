<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u-a5b7bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:split-horizontal-32-filled" {...props}></Icon>
<style>
:global(.u-a5b7bxo) {
  fill: currentColor;
  d: path("M3 15a1 1 0 1 0 0 2h26a1 1 0 1 0 0-2zm3 11.5v-8h20v8a3.5 3.5 0 0 1-3.5 3.5h-13A3.5 3.5 0 0 1 6 26.5m20-13v-8A3.5 3.5 0 0 0 22.5 2h-13A3.5 3.5 0 0 0 6 5.5v8z");
}

</style>

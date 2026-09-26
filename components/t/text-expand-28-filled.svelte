<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="wu1vs1qdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-expand-28-filled" {...props}></Icon>
<style>
:global(.wu1vs1qdg) {
  fill: currentColor;
  d: path("M25 22a1 1 0 1 1 0 2H7a1 1 0 1 1 0-2zM7.5 8a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m0 2a.5.5 0 0 0-.5.5V13H4.5a.5.5 0 0 0 0 1H7v2.5a.5.5 0 0 0 1 0V14h2.5a.5.5 0 0 0 0-1H8v-2.5a.5.5 0 0 0-.5-.5M25 16a1 1 0 1 1 0 2h-9a1 1 0 1 1 0-2zm0-6a1 1 0 1 1 0 2h-9a1 1 0 1 1 0-2zm0-6a1 1 0 1 1 0 2H7a1 1 0 0 1 0-2z");
}

</style>

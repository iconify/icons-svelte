<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sh1gadh1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:textbox-align-middle-left-16-filled" {...props}></Icon>
<style>
:global(.sh1gadh1n) {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v7A2.5 2.5 0 0 0 4.5 14h7a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 11.5 2zm1 4h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1m0 3h3a.5.5 0 0 1 0 1h-3a.5.5 0 0 1 0-1");
}

</style>

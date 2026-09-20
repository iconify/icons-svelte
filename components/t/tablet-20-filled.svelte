<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fwi596aim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:tablet-20-filled" {...props}></Icon>
<style>
:global(.fwi596aim) {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2zm6.5 6a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1z");
}

</style>

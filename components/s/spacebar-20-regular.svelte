<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w535gjbhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:spacebar-20-regular" {...props}></Icon>
<style>
:global(.w535gjbhw) {
  fill: currentColor;
  d: path("M2.5 8a.5.5 0 0 1 .5.5v2a.5.5 0 0 0 .5.5h13a.5.5 0 0 0 .5-.5v-2a.5.5 0 0 1 1 0v2a1.5 1.5 0 0 1-1.5 1.5h-13A1.5 1.5 0 0 1 2 10.5v-2a.5.5 0 0 1 .5-.5");
}

</style>

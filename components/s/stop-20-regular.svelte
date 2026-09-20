<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tmpp37-gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:stop-20-regular" {...props}></Icon>
<style>
:global(.tmpp37-gs) {
  fill: currentColor;
  d: path("M15.5 4a.5.5 0 0 1 .5.5v11a.5.5 0 0 1-.5.5h-11a.5.5 0 0 1-.5-.5v-11a.5.5 0 0 1 .5-.5zm-11-1A1.5 1.5 0 0 0 3 4.5v11A1.5 1.5 0 0 0 4.5 17h11a1.5 1.5 0 0 0 1.5-1.5v-11A1.5 1.5 0 0 0 15.5 3z");
}

</style>

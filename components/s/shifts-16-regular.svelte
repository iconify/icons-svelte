<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="aghdxy0ij"/><path class="j7kvfmbxr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:shifts-16-regular" {...props}></Icon>
<style>
:global(.aghdxy0ij) {
  d: path("M7.5 4a.5.5 0 0 1 .5.5V8h2.5a.5.5 0 0 1 0 1h-3a.5.5 0 0 1-.5-.5v-4a.5.5 0 0 1 .5-.5");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.j7kvfmbxr) {
  d: path("M4.497 2a2.5 2.5 0 0 0-2.5 2.5v7a2.5 2.5 0 0 0 2.5 2.5h7a2.5 2.5 0 0 0 2.5-2.5v-7a2.5 2.5 0 0 0-2.5-2.5zm-1.5 2.5a1.5 1.5 0 0 1 1.5-1.5h7a1.5 1.5 0 0 1 1.5 1.5v7a1.5 1.5 0 0 1-1.5 1.5h-7a1.5 1.5 0 0 1-1.5-1.5z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="zf1tvej-c"/><path class="ol4k1c6af"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:tablet" {...props}></Icon>
<style>
:global(.n1lsf0bnc) {
  fill: currentColor;
  fill-rule: evenodd;
}

:global(.ol4k1c6af) {
  d: path("M7.75 16a1 1 0 0 1 1-1h2.5a1 1 0 1 1 0 2h-2.5a1 1 0 0 1-1-1");
}

:global(.zf1tvej-c) {
  d: path("M1.5 2a2 2 0 0 1 2-2h13a2 2 0 0 1 2 2v16a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2zm15 0h-13v16h13z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="iwly1cb7u"/><path class="xpaem9blu"/><path class="j6m96f7cc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:television" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.iwly1cb7u) {
  fill-rule: evenodd;
  d: path("M2 8v7a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3V8a3 3 0 0 0-3-3H5a3 3 0 0 0-3 3m3 8a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1z");
}

:global(.j6m96f7cc) {
  d: path("M8.72 5.625a1 1 0 0 0 1.56-1.25l-2-2.5a1 1 0 0 0-1.56 1.25z");
}

:global(.xpaem9blu) {
  d: path("M11.28 5.625a1 1 0 0 1-1.56-1.25l2-2.5a1 1 0 0 1 1.56 1.25z");
}

</style>

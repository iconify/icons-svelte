<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="q_e12wb3s"/><path class="z-ut9_bom"/><path class="axbcvsb8z"/><path class="nlauy9eoa"/><path class="gbx4dthet"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:sort" {...props}></Icon>
<style>
:global(.axbcvsb8z) {
  d: path("M14 5a1 1 0 0 1 1 1v8a1 1 0 1 1-2 0V6a1 1 0 0 1 1-1m-4.293 7.293a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0");
}

:global(.gbx4dthet) {
  d: path("M6 15a1 1 0 0 1-1-1V6a1 1 0 1 1 2 0v8a1 1 0 0 1-1 1");
}

:global(.n1lsf0bnc) {
  fill: currentColor;
  fill-rule: evenodd;
}

:global(.nlauy9eoa) {
  d: path("M2.293 12.293a1 1 0 0 1 1.414 0l3 3a1 1 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414");
}

:global(.q_e12wb3s) {
  d: path("M10.293 7.707a1 1 0 0 1 0-1.414l3-3a1 1 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0");
}

:global(.z-ut9_bom) {
  d: path("M17.707 7.707a1 1 0 0 1-1.414 0l-3-3a1 1 0 0 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ude7twc4s"/><path clip-rule="evenodd" class="p9w_x75yf"/><path clip-rule="evenodd" class="nx53exbvi"/><path clip-rule="evenodd" class="ag2kz-bnv"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:yuan-off" {...props}></Icon>
<style>
:global(.ag2kz-bnv) {
  fill-rule: evenodd;
  d: path("M10 9a1 1 0 0 1 1 1v7a1 1 0 1 1-2 0v-7a1 1 0 0 1 1-1");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.nx53exbvi) {
  fill-rule: evenodd;
  d: path("M4.5 11a1 1 0 0 1 1-1h9a1 1 0 1 1 0 2h-9a1 1 0 0 1-1-1");
}

:global(.p9w_x75yf) {
  fill-rule: evenodd;
  d: path("M15.581 2.186a1 1 0 0 0-1.395.233l-5 7a1 1 0 0 0 1.628 1.162l5-7a1 1 0 0 0-.233-1.395");
}

:global(.ude7twc4s) {
  fill-rule: evenodd;
  d: path("M4.419 2.186a1 1 0 0 1 1.395.233l5 7a1 1 0 1 1-1.628 1.162l-5-7a1 1 0 0 1 .233-1.395");
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>

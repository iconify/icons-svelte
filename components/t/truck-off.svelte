<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ycumi-5ma"/><path clip-rule="evenodd" class="mym9o3lhb"/><path class="p-oihopda"/><path clip-rule="evenodd" class="pzn77cc3b"/><path class="q9alg6bbv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:truck-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.mym9o3lhb) {
  fill-rule: evenodd;
  d: path("M18 4.5H8a2 2 0 0 0-2 2V14a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V6.5a2 2 0 0 0-2-2M8 14V6.5h10V14z");
}

:global(.p-oihopda) {
  d: path("M10.25 8.75a.5.5 0 0 1 0-1h5.5a.5.5 0 0 1 0 1zm0 2a.5.5 0 0 1 0-1h5.5a.5.5 0 0 1 0 1zm0 2a.5.5 0 0 1 0-1h5.5a.5.5 0 0 1 0 1z");
}

:global(.pzn77cc3b) {
  fill-rule: evenodd;
  d: path("M6 7.5H2.736a2 2 0 0 0-1.92 1.442L0 11.75V14a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V9.5a2 2 0 0 0-2-2M2 14v-1.966L2.736 9.5H6V14z");
}

:global(.q9alg6bbv) {
  d: path("M3.29 10.1H5a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.5.5H3a.5.5 0 0 1-.5-.5v-.85l.015-.122l.29-1.15a.5.5 0 0 1 .485-.378M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

:global(.ycumi-5ma) {
  d: path("M7.5 18.75a2.25 2.25 0 1 1 0-4.5a2.25 2.25 0 0 1 0 4.5m9 0a2.25 2.25 0 1 1 0-4.5a2.25 2.25 0 0 1 0 4.5");
}

</style>

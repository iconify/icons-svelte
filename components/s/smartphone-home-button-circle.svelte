<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="z--84pbxy"/><path class="y79x3prpc"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:smartphone-home-button-circle" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.kphejjb8s) {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

:global(.y79x3prpc) {
  d: path("M13 20.25a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5");
}

:global(.z--84pbxy) {
  fill-rule: evenodd;
  d: path("M17.5 3h-9a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h9a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2m-9 18V5h9v16z");
}

</style>

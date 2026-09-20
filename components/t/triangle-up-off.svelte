<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="n_ly-mb6l"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:triangle-up-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.n_ly-mb6l) {
  fill-rule: evenodd;
  d: path("M10 7.002L5.963 14h8.074zm.866-2.5a1 1 0 0 0-1.732 0L3.365 14.5a1 1 0 0 0 .866 1.5H15.77a1 1 0 0 0 .866-1.5z");
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="haosz1bif"/><path class="yi6zc2_0n"/><path class="gjo-9sz6n"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:scissors-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.gjo-9sz6n) {
  d: path("M6.793 11.293a1 1 0 1 0 1.414 1.414l8.5-8.5a1 1 0 0 0-1.414-1.414z");
}

:global(.haosz1bif) {
  fill-rule: evenodd;
  d: path("M2 5.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 0 0-7 0m5 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0M2 14a3.5 3.5 0 1 0 7 0a3.5 3.5 0 0 0-7 0m5 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

:global(.yi6zc2_0n) {
  d: path("M16.707 15.293a1 1 0 0 1-1.414 1.414l-8.5-8.5a1 1 0 0 1 1.414-1.414z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ux5geopgl"/><path class="xe6xp2b4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:sim-card-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ux5geopgl) {
  d: path("M176 120v72H80v-72Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xe6xp2b4i) {
  d: path("m213.66 82.34l-56-56A8 8 0 0 0 152 24H56a16 16 0 0 0-16 16v176a16 16 0 0 0 16 16h144a16 16 0 0 0 16-16V88a8 8 0 0 0-2.34-5.66M200 216H56V40h92.69L200 91.31zm-24-104H80a8 8 0 0 0-8 8v72a8 8 0 0 0 8 8h96a8 8 0 0 0 8-8v-72a8 8 0 0 0-8-8m-8 72h-16v-32a8 8 0 0 0-16 0v32h-16v-32a8 8 0 0 0-16 0v32H88v-56h80Z");
}

</style>

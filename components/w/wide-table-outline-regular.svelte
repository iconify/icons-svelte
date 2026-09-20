<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="murw5tb-p"/><path class="nj-oiubfo"/><path class="sunqexbsa"/><path class="x26a8iq1c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wide-table-outline-regular" {...props}></Icon>
<style>
:global(.murw5tb-p) {
  d: path("M2 9a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.nj-oiubfo) {
  d: path("M8 7v10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sunqexbsa) {
  d: path("M16 7v10");
}

:global(.x26a8iq1c) {
  d: path("M2 12h20");
}

</style>

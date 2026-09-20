<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tt7ypiikb"/><path class="n-059ea3n"/><path class="du3agkbjb"/><path class="wew0vnk_n"/><path class="olmwgycdy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:srm-check-outline-bold" {...props}></Icon>
<style>
:global(.du3agkbjb) {
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.n-059ea3n) {
  d: path("M5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.olmwgycdy) {
  d: path("M15 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tt7ypiikb) {
  d: path("M5 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.wew0vnk_n) {
  d: path("M12 5v14");
}

</style>

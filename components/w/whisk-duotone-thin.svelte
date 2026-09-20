<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m471kbbab"/><path class="hme2y-bmh"/><path class="zhy6yeb4j"/><path class="ecxgw5evs"/><path class="z_j864liq"/><path class="hx7cfzbbm"/><path class="l6rp-_-ny"/><path class="mww7ccc2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:whisk-duotone-thin" {...props}></Icon>
<style>
:global(.ecxgw5evs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 21c0 -6 -1 -12 -2 -12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hme2y-bmh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 21c0 -6 2 -12 6 -12s6 6 6 12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hx7cfzbbm) {
  d: path("M6 21c0 -6 2 -12 6 -12s6 6 6 12");
}

:global(.l6rp-_-ny) {
  d: path("M10 21c0 -6 1 -12 2 -12");
}

:global(.m471kbbab) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 2v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mww7ccc2b) {
  d: path("M14 21c0 -6 -1 -12 -2 -12");
}

:global(.z_j864liq) {
  d: path("M12 2v7");
}

:global(.zhy6yeb4j) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 21c0 -6 1 -12 2 -12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

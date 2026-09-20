<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="le0g-d6db"/><path class="kgyvi50al"/><path class="prbs3ccnp"/><path class="eki_s5bnj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:turn-right-duotone-regular" {...props}></Icon>
<style>
:global(.eki_s5bnj) {
  d: path("m14 6 3 3 -3 3");
}

:global(.kgyvi50al) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14 6 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.le0g-d6db) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 21V9h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.prbs3ccnp) {
  d: path("M8 21V9h9");
}

</style>

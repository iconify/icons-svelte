<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n48w5yb-p"/><path class="uhawluh-v"/><path class="b08-3-b7u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:table-cells-merge-outline-regular" {...props}></Icon>
<style>
:global(.b08-3-b7u) {
  d: path("M17.5 9.5 15 12l2.5 2.5");
}

:global(.n48w5yb-p) {
  d: path("M14 4h5a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uhawluh-v) {
  d: path("M6.5 9.5 9 12l-2.5 2.5");
}

</style>

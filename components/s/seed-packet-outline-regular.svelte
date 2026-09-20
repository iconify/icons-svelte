<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d7j29trjs"/><path class="f8gsx7b5s"/><path class="p-3tqnbzb"/><path class="ak_t1bcfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:seed-packet-outline-regular" {...props}></Icon>
<style>
:global(.ak_t1bcfw) {
  d: path("M14 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.d7j29trjs) {
  d: path("M6 4h12v16H6Z");
}

:global(.f8gsx7b5s) {
  d: path("M6 8h12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p-3tqnbzb) {
  d: path("M9 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>

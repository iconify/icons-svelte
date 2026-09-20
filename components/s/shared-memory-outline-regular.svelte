<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n0n63pb2v"/><path class="p3mjlkbpz"/><path class="ij7rtuuan"/><path class="ayvbjgbud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shared-memory-outline-regular" {...props}></Icon>
<style>
:global(.ayvbjgbud) {
  d: path("M10.5 8h3");
}

:global(.ij7rtuuan) {
  d: path("M13.5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.n0n63pb2v) {
  d: path("M4 15v4h16v-4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p3mjlkbpz) {
  d: path("M6.5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

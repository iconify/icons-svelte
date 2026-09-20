<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nnzlfsekh"/><path class="o19v3ublc"/><path class="f28fgsruz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:savings-plan-outline-regular" {...props}></Icon>
<style>
:global(.f28fgsruz) {
  d: path("m13 15 2 2 5 -5");
}

:global(.nnzlfsekh) {
  d: path("M2 8a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o19v3ublc) {
  d: path("M5 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gcyir0cbn"/><path class="qbme7ibis"/><path class="arrljibna"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sponge-outline-regular" {...props}></Icon>
<style>
:global(.arrljibna) {
  d: path("M14 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gcyir0cbn) {
  d: path("M4 10a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qbme7ibis) {
  d: path("M4 12c2 -2 4 2 6 0s4 2 6 0 3 1 4 0");
}

</style>

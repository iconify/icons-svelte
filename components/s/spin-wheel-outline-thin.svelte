<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nqda50bqs"/><path class="bg2ejdbaq"/><path class="urilmibxp"/><path class="x37ahcyum"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:spin-wheel-outline-thin" {...props}></Icon>
<style>
:global(.bg2ejdbaq) {
  d: path("M12 5v16");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nqda50bqs) {
  d: path("M4 13a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

:global(.urilmibxp) {
  d: path("M4 13h16");
}

:global(.x37ahcyum) {
  d: path("M9 2h6l-3 3Z");
}

</style>

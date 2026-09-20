<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xvabp0bhv"/><path class="m8h6hlbgk"/><path class="uux3anbrn"/><path class="yyqghmoaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:school-ruler-outline-regular" {...props}></Icon>
<style>
:global(.m8h6hlbgk) {
  d: path("m5 13 3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uux3anbrn) {
  d: path("m9 9 3 3");
}

:global(.xvabp0bhv) {
  d: path("M2 16 16 2l6 6L8 22Z");
}

:global(.yyqghmoaf) {
  d: path("m13 5 3 3");
}

</style>

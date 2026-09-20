<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cxzkdrccx"/><path class="r5_3r9_hf"/><path class="dk2_9r6pl"/><path class="mt0duqbnk"/><path class="xlekzhbnl"/><path class="o8od38cnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sort-asc-duotone-regular" {...props}></Icon>
<style>
:global(.cxzkdrccx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dk2_9r6pl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mt0duqbnk) {
  d: path("M4 6h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.r5_3r9_hf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xlekzhbnl) {
  d: path("M4 12h11");
}

</style>

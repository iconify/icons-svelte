<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s9cv4hbfr"/><path class="oe0l5gshl"/><path class="t-3ggyssa"/><path class="nbsfmkbol"/><path class="eah0r8b_w"/><path class="x2b10gplf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:speaker-diarize-duotone-thin" {...props}></Icon>
<style>
:global(.eah0r8b_w) {
  d: path("M19.19 3.37a4 4 0 1 1 -3.38 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nbsfmkbol) {
  d: path("M8.19 3.37a4 4 0 1 1 -3.38 0");
}

:global(.oe0l5gshl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19.19 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s9cv4hbfr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.19 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t-3ggyssa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 17 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x2b10gplf) {
  d: path("m3 17 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

</style>

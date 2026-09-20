<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sue0rgi5i"/><path class="j1csxbc-h"/><path class="q71rf2zhu"/><path class="sqsxh9blm"/><path class="tklpoac2f"/><path class="ui32hib9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:text-color-duotone-regular" {...props}></Icon>
<style>
:global(.j1csxbc-h) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 5v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q71rf2zhu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 20h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sqsxh9blm) {
  d: path("M5 5h14");
}

:global(.sue0rgi5i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 5h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tklpoac2f) {
  d: path("M12 5v10");
}

:global(.ui32hib9b) {
  d: path("M5 20h14");
}

</style>

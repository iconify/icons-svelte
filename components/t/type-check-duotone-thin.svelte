<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fo9xftbee"/><path class="p-vy29bom"/><path class="frjwwxm7e"/><path class="atcmxjbma"/><path class="p4idz7btn"/><path class="h6srt4n9a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:type-check-duotone-thin" {...props}></Icon>
<style>
:global(.atcmxjbma) {
  d: path("M4 5h12");
}

:global(.fo9xftbee) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.frjwwxm7e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 15 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h6srt4n9a) {
  d: path("m14 15 3 3 5 -5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p-vy29bom) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 5v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p4idz7btn) {
  d: path("M10 5v10");
}

</style>

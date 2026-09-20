<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i3t090twc"/><path class="z2xx1pboh"/><path class="am7eiccgy"/><path class="p7nia1b6j"/><path class="h50arts9k"/><path class="x3jqftbaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:span-trace-duotone-thin" {...props}></Icon>
<style>
:global(.am7eiccgy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h50arts9k) {
  d: path("M6 12h10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i3t090twc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 7h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p7nia1b6j) {
  d: path("M3 7h16");
}

:global(.x3jqftbaj) {
  d: path("M9 17h12");
}

:global(.z2xx1pboh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dbp9eobfb"/><path class="qn-opib9b"/><path class="cmdo5slre"/><path class="p7nia1b6j"/><path class="h50arts9k"/><path class="x3jqftbaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:span-trace-duotone-bold" {...props}></Icon>
<style>
:global(.cmdo5slre) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dbp9eobfb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 7h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h50arts9k) {
  d: path("M6 12h10");
}

:global(.p7nia1b6j) {
  d: path("M3 7h16");
}

:global(.qn-opib9b) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x3jqftbaj) {
  d: path("M9 17h12");
}

</style>

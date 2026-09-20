<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rxwr8htky"/><path class="mqz458_ps"/><path class="any2y0bvq"/><path class="nx1eh8hxp"/><path class="rdhgnbc4d"/><path class="qno8l4b9z"/><path class="nuz6-76is"/><path class="l3ca9u8kt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tournament-bracket-duotone-regular" {...props}></Icon>
<style>
:global(.any2y0bvq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19h6v-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l3ca9u8kt) {
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.mqz458_ps) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h6v7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nuz6-76is) {
  d: path("M15 12h6");
}

:global(.nx1eh8hxp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qno8l4b9z) {
  d: path("M3 19h6v-7");
}

:global(.rdhgnbc4d) {
  d: path("M3 5h6v7h6");
}

:global(.rxwr8htky) {
  fill: currentColor;
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

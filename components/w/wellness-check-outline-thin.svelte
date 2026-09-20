<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z7796cdhw"/><path class="yok9qsxfg"/><path class="rm9_1_hyj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wellness-check-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rm9_1_hyj) {
  d: path("M16 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.yok9qsxfg) {
  d: path("M19 8v5");
}

:global(.z7796cdhw) {
  d: path("M3 12a3.5 3.5 0 0 1 7 0 3.5 3.5 0 0 1 7 0l-7 7Z");
}

</style>

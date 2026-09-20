<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wf7fbvbzh"/><path class="akyaa-boy"/><path class="nuk2gwb4b"/><path class="gstzuxb9r"/><path class="ldq326b0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trumpet-duotone-thin" {...props}></Icon>
<style>
:global(.akyaa-boy) {
  d: path("M13 11H2v4h11");
}

:global(.gstzuxb9r) {
  d: path("M5 7v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ldq326b0y) {
  d: path("M9 7v4");
}

:global(.nuk2gwb4b) {
  d: path("m13 9 6 -6v18l-6 -6Z");
}

:global(.wf7fbvbzh) {
  fill: currentColor;
  d: path("m13 9 6 -6v18l-6 -6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

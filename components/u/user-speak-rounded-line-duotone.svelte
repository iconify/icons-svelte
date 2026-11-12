<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="o_onwfy1m"/><ellipse class="u38oezbao"/><path class="sfxgh6bez"/><path class="d8f9mr75j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-speak-rounded-line-duotone" {...props}></Icon>
<style>
:global(.d8f9mr75j) {
  d: path("M17 4C17 4 18 4.6 18 6C18 7.4 17 8 17 8");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o_onwfy1m) {
  cx: 10px;
  cy: 6px;
  r: 4px;
}

:global(.sfxgh6bez) {
  d: path("M19 2C19 2 21 3.2 21 6C21 8.8 19 10 19 10");
}

:global(.u38oezbao) {
  cx: 10px;
  cy: 17px;
  opacity: var(--svg-opacity--0-5, 0.5);
  rx: 7px;
  ry: 4px;
}

</style>

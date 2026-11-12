<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="o_onwfy1m"/><path class="geogrv1gb"/><path class="sfxgh6bez"/><path class="d8f9mr75j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-speak-linear" {...props}></Icon>
<style>
:global(.d8f9mr75j) {
  d: path("M17 4C17 4 18 4.6 18 6C18 7.4 17 8 17 8");
}

:global(.geogrv1gb) {
  d: path("M18 17.5C18 19.9853 18 22 10 22C2 22 2 19.9853 2 17.5C2 15.0147 5.58172 13 10 13C14.4183 13 18 15.0147 18 17.5Z");
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

</style>

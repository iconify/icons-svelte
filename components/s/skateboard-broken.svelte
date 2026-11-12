<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jjrrsabdw"/><circle class="x9u4_etvk"/><circle class="z7l_f7r4c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:skateboard-broken" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jjrrsabdw) {
  d: path("M2 7L2.81253 8.2188C3.5544 9.3316 4.80332 10 6.14073 10H12M22 7L21.1875 8.2188C20.4456 9.33159 19.1967 10 17.8593 10H16");
}

:global(.x9u4_etvk) {
  cx: 7px;
  cy: 15px;
  r: 2px;
}

:global(.z7l_f7r4c) {
  cx: 17px;
  cy: 15px;
  r: 2px;
}

</style>

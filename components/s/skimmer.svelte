<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="pn8ouyydo"/><path class="ci2lgptiq"/><path class="t5tekyfbb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:skimmer" {...props}></Icon>
<style>
:global(.ci2lgptiq) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 13.5h.01m3.99 0h.01m-4.01 3h.01m3.99 0h.01");
}

:global(.pn8ouyydo) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15a6.5 4.25 0 1 0 13 0a6.5 4.25 0 1 0-13 0");
}

:global(.t5tekyfbb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.23 12.27l6.52-8.02");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

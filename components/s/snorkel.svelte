<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z-ldr81si"/><path class="jz67m_bzv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:snorkel" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jz67m_bzv) {
  d: path("M20.5 2.75V16.5a4.25 4.25 0 0 1-4.25 4.25H13.5v-2");
}

:global(.z-ldr81si) {
  d: path("M2.75 10.5a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2v3a3 3 0 0 1-3 3h-1.5l-2.25-2l-2.25 2h-3a3 3 0 0 1-3-3Z");
}

</style>

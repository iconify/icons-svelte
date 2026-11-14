<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ht6pt40ib"/><path class="z0h8v-qvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:text-translate" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ht6pt40ib) {
  d: path("m3.5 12.5l4-8.5l4 8.5M5 9.5h5m3.5 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0m6-3v6M14 4h3a2.5 2.5 0 0 1 2.5 2.5v3");
}

:global(.z0h8v-qvv) {
  d: path("m18 8l1.5 1.5L21 8");
}

</style>

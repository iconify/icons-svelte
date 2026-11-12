<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nx9b_s0ui"/><path class="ip_zkkjah"/><path class="rna54ibnn"/><path class="g40pzzt0z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wi-fi-linear" {...props}></Icon>
<style>
:global(.g40pzzt0z) {
  stroke-linejoin: round;
  d: path("M12.0176 19.4641H12.0177");
}

:global(.ip_zkkjah) {
  d: path("M5.33301 12.2948C9.01491 8.32068 14.9844 8.32068 18.6663 12.2948");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nx9b_s0ui) {
  d: path("M8.66699 15.8931C10.5079 13.9061 13.4927 13.9061 15.3337 15.8931");
}

:global(.rna54ibnn) {
  d: path("M2 8.69718C7.52285 2.73603 16.4772 2.73603 22 8.69718");
}

</style>

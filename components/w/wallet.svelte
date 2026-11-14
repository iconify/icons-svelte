<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mf320p9is"/><path class="vaxemf0zs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wallet" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mf320p9is) {
  d: path("M7.375 4.5h9.25A4.375 4.375 0 0 1 21 8.875v6.25a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 15.125v-6.25A4.375 4.375 0 0 1 7.375 4.5");
}

:global(.vaxemf0zs) {
  d: path("M21 9.5h-4a2.5 2.5 0 0 0 0 5h4");
}

</style>

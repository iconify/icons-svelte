<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y8rchkbuh"/><path class="jgeg8bc0n"/><path class="zvlywgbxr"/><path class="dnytl_40k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-align-left-linear" {...props}></Icon>
<style>
:global(.dnytl_40k) {
  d: path("M5 18H14");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jgeg8bc0n) {
  d: path("M5 10H14");
}

:global(.y8rchkbuh) {
  d: path("M5 6H19");
}

:global(.zvlywgbxr) {
  d: path("M5 14H19");
}

</style>

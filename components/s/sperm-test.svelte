<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aurgfjb-h"/><path class="pbeiyabda"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sperm-test" {...props}></Icon>
<style>
:global(.aurgfjb-h) {
  d: path("M11.5 7a3.5 2.5 0 1 0 7 0a3.5 2.5 0 1 0-7 0m1 2.5C10 12 12 14 9.5 16S5 17.5 3 21m13.25-6.75v5.25c0 2.25 3.5 2.25 3.5 0v-5.25m-4.5 0h5.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pbeiyabda) {
  fill: currentColor;
  d: path("M16.25 17.5h3.5v2c0 2.25-3.5 2.25-3.5 0Z");
}

</style>

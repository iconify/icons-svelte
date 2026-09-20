<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lhk-ji-wo"/><path class="z22xlf92i"/><path class="hue5ncbwv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vegetable-basket-outline-regular" {...props}></Icon>
<style>
:global(.hue5ncbwv) {
  d: path("M7 12a5 5 0 0 1 10 0");
}

:global(.lhk-ji-wo) {
  d: path("M5 12v8h14v-8Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.z22xlf92i) {
  d: path("M5 16h14");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t03dwshwl"/><path class="ywohddcxs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:water-intake-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t03dwshwl) {
  d: path("M7 11v6l3 3h4l3 -3v-6");
}

:global(.ywohddcxs) {
  d: path("M12 2.5 15.5 6a3.5 3.5 0 1 1 -7 0Z");
}

</style>

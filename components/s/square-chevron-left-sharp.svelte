<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="x-_5ilohg"/><path class="gn4znuuld"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-chevron-left-sharp" {...props}></Icon>
<style>
:global(.gn4znuuld) {
  d: path("M14.2929 7.7071L10 12L14.2929 16.2929");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x-_5ilohg) {
  d: path("M3 3L21 3L21 21L3 21L3 3Z");
}

</style>

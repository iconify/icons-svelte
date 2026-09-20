<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lokgnabwi"/><path class="i4kf51esh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:token-limit-outline-regular" {...props}></Icon>
<style>
:global(.i4kf51esh) {
  d: path("M19 5v14");
}

:global(.lokgnabwi) {
  d: path("M3 12a3 3 0 0 1 3 -3h7a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

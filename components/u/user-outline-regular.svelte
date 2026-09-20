<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ufzn_r3vk"/><path class="bt921xbxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:user-outline-regular" {...props}></Icon>
<style>
:global(.bt921xbxy) {
  d: path("M5 21a7 7 0 0 1 14 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ufzn_r3vk) {
  d: path("M9 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rmqlc6x4e"/><path class="dx93_50hj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:test-tube-sharp-fill" {...props}></Icon>
<style>
:global(.dx93_50hj) {
  d: path("M7 2L17 2");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rmqlc6x4e) {
  fill: currentColor;
  d: path("M9 1L15 1C15.5523 1 16 1.4477 16 2L16 19C16 21.2091 14.2091 23 12 23C9.7909 23 8 21.2091 8 19L8 2C8 1.4477 8.4477 1 9 1ZM10 3L10 13L14 13L14 3L10 3Z");
  stroke: none;
}

</style>

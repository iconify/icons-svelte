<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ctkwnzbjp"/><path class="fiecv05co"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:smartphone-arrow-in-up-right-sharp-two-tone" {...props}></Icon>
<style>
:global(.ctkwnzbjp) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 2L20 12C20 12.5523 19.5523 13 19 13L10 13L10 22C10 22.5523 9.5523 23 9 23C6.2386 23 4 20.7614 4 18L4 2C4 1.4477 4.4477 1 5 1L19 1C19.5523 1 20 1.4477 20 2Z");
  stroke: none;
}

:global(.fiecv05co) {
  d: path("M19 13L19 2L5 2L5 22L10 22M14.5 6L9.5 6M12 16L19 16L19 23M13.7071 21.2929L18.8536 16.1464");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

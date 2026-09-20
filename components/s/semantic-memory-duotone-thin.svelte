<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u2t7v6bmy"/><path class="qd2a5rnak"/><path class="sfb1ntbvv"/><path class="zwghjjvbs"/><path class="w-gst71bz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:semantic-memory-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qd2a5rnak) {
  d: path("M2 6h7");
}

:global(.sfb1ntbvv) {
  d: path("M2 11h7");
}

:global(.u2t7v6bmy) {
  fill: currentColor;
  d: path("m17 7 4 4 -4 4 -4 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.w-gst71bz) {
  d: path("m17 7 4 4 -4 4 -4 -4Z");
}

:global(.zwghjjvbs) {
  d: path("M2 16h7");
}

</style>

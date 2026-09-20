<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qd2a5rnak"/><path class="sfb1ntbvv"/><path class="zwghjjvbs"/><path class="w-gst71bz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:semantic-memory-outline-bold" {...props}></Icon>
<style>
:global(.qd2a5rnak) {
  d: path("M2 6h7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sfb1ntbvv) {
  d: path("M2 11h7");
}

:global(.w-gst71bz) {
  d: path("m17 7 4 4 -4 4 -4 -4Z");
}

:global(.zwghjjvbs) {
  d: path("M2 16h7");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="myt_b32pc"/><path class="y29zmn0-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shellfish-allergy-outline-bold" {...props}></Icon>
<style>
:global(.myt_b32pc) {
  d: path("M4 18a8 8 0 0 1 16 0Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.y29zmn0-m) {
  d: path("M5 20 19 6");
}

</style>

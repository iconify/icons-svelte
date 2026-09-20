<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="a7juzblmp"/><path class="nwr6yccba"/><path class="xec9ltb1w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wellbeing-goal-outline-bold" {...props}></Icon>
<style>
:global(.a7juzblmp) {
  d: path("M5 12a3 3 0 0 1 6 0 3 3 0 0 1 6 0l-6 6Z");
}

:global(.nwr6yccba) {
  d: path("M20 7v7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xec9ltb1w) {
  d: path("m20 3 -4 4h4Z");
}

</style>

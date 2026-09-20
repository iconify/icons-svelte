<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ujm7rsigg"/><path class="k43oxubtv"/><path class="ms-bankjf"/><path class="x8p5627ac"/><path class="gcalxb98a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sim-card-duotone-bold" {...props}></Icon>
<style>
:global(.gcalxb98a) {
  d: path("M8 13h8");
}

:global(.k43oxubtv) {
  fill: currentColor;
  d: path("M8 11a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ms-bankjf) {
  d: path("M9 2h11v20H4V7Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ujm7rsigg) {
  fill: currentColor;
  d: path("M9 2h11v20H4V7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x8p5627ac) {
  d: path("M8 11a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

</style>

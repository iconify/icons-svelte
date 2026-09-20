<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x1t_rfh5c"/><path class="hspeesv2z"/><path class="ujt25lh2u"/><path class="tv6hbrcra"/><path class="y2dvsvbhm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:saved-goal-duotone-bold" {...props}></Icon>
<style>
:global(.hspeesv2z) {
  d: path("M5.5 3v5.5a6.5 6.5 0 0 0 13 0V3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tv6hbrcra) {
  d: path("M8.5 20.5h7");
}

:global(.ujt25lh2u) {
  d: path("M12 15v5.5");
}

:global(.x1t_rfh5c) {
  fill: currentColor;
  d: path("M10 6h4v6l-2 -2 -2 2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.y2dvsvbhm) {
  d: path("M10 6h4v6l-2 -2 -2 2Z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pv7_hab2r"/><path class="f0_7ifg4g"/><path class="v_e4fzbym"/><path class="tx6qscbul"/><path class="uk7acdcay"/><path class="b4de0eyhw"/><path class="lxtc-wp5b"/><path class="s-cqkabbd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:socket-close-duotone-bold" {...props}></Icon>
<style>
:global(.b4de0eyhw) {
  d: path("M16 4h4v16h-4");
}

:global(.f0_7ifg4g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 4h4v16h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lxtc-wp5b) {
  d: path("m10 10 4 4");
}

:global(.pv7_hab2r) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 4H4v16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s-cqkabbd) {
  d: path("m14 10 -4 4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tx6qscbul) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 10 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uk7acdcay) {
  d: path("M8 4H4v16h4");
}

:global(.v_e4fzbym) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 10 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mbmrpw-rs"/><path class="v79iaqbup"/><path class="hbz-npylq"/><path class="j5qohtzrk"/><path class="ae-e09b3w"/><path class="f-g2d4bkj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wind-gust-duotone-bold" {...props}></Icon>
<style>
:global(.ae-e09b3w) {
  d: path("M3 12h18");
}

:global(.f-g2d4bkj) {
  d: path("M8 17h10");
}

:global(.hbz-npylq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 17h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j5qohtzrk) {
  d: path("M6 7h10");
}

:global(.mbmrpw-rs) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 7h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v79iaqbup) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

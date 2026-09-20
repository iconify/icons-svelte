<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yb522ge7e"/><path class="onkakwu-v"/><path class="nf7-vla4l"/><path class="ix7nm4b_a"/><path class="g8q62k13p"/><path class="n49oq7__n"/><path class="kt4vswbcx"/><path class="u9ungwb-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:voice-clone-duotone-bold" {...props}></Icon>
<style>
:global(.g8q62k13p) {
  d: path("M5.88 14.12a3 3 0 0 1 0 -4.24");
}

:global(.ix7nm4b_a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20.24 7.76a6 6 0 0 1 0 8.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kt4vswbcx) {
  d: path("M18.12 9.88a3 3 0 0 1 0 4.24");
}

:global(.n49oq7__n) {
  d: path("M3.76 16.24a6 6 0 0 1 0 -8.5");
}

:global(.nf7-vla4l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18.12 9.88a3 3 0 0 1 0 4.24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.onkakwu-v) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3.76 16.24a6 6 0 0 1 0 -8.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u9ungwb-f) {
  d: path("M20.24 7.76a6 6 0 0 1 0 8.5");
}

:global(.yb522ge7e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.88 14.12a3 3 0 0 1 0 -4.24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

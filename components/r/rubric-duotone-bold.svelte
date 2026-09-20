<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wvd8g1bvl"/><path class="lypr0rbtj"/><path class="dkassww8z"/><path class="i5tmmsb7a"/><path class="dm_ar8wjk"/><path class="b5p141rkx"/><path class="u9jggobpf"/><path class="cre86eeda"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rubric-duotone-bold" {...props}></Icon>
<style>
:global(.b5p141rkx) {
  d: path("M11 7.5h10");
}

:global(.cre86eeda) {
  d: path("M11 15.5h10");
}

:global(.dkassww8z) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 15 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dm_ar8wjk) {
  d: path("m3 7 2 2 3 -3");
}

:global(.i5tmmsb7a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 15.5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lypr0rbtj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 7.5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u9jggobpf) {
  d: path("m3 15 2 2 3 -3");
}

:global(.wvd8g1bvl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 7 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

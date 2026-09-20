<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ccvs8vkcj"/><path class="hj963orqe"/><path class="bfq_3ybee"/><path class="h37wig_dz"/><path class="dm_ar8wjk"/><path class="b5p141rkx"/><path class="u9jggobpf"/><path class="cre86eeda"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rubric-duotone-thin" {...props}></Icon>
<style>
:global(.b5p141rkx) {
  d: path("M11 7.5h10");
}

:global(.bfq_3ybee) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 15 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ccvs8vkcj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 7 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cre86eeda) {
  d: path("M11 15.5h10");
}

:global(.dm_ar8wjk) {
  d: path("m3 7 2 2 3 -3");
}

:global(.h37wig_dz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 15.5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hj963orqe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 7.5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u9jggobpf) {
  d: path("m3 15 2 2 3 -3");
}

</style>

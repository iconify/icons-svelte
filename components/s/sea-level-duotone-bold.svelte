<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aep_ellef"/><path class="zhxt7nh4s"/><path class="qwaphmbjf"/><path class="daxdrrb0a"/><path class="b-rxu8bqf"/><path class="ftqzjnb8u"/><path class="a23llpbrh"/><path class="ta7smn7pq"/><path class="s09jr7bxh"/><path class="gj9xsebsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sea-level-duotone-bold" {...props}></Icon>
<style>
:global(.a23llpbrh) {
  d: path("M4 3h4");
}

:global(.aep_ellef) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.b-rxu8bqf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 20 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.daxdrrb0a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 15 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ftqzjnb8u) {
  d: path("M6 3v18");
}

:global(.gj9xsebsr) {
  d: path("m9 20 3 -3 3 3 3 -3 3 3");
}

:global(.qwaphmbjf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 9h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s09jr7bxh) {
  d: path("m9 15 3 -3 3 3 3 -3 3 3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ta7smn7pq) {
  d: path("M4 9h4");
}

:global(.zhxt7nh4s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

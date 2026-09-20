<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e03qxmiyg"/><path class="ar5lnnlvf"/><path class="h95es8zjt"/><path class="n9mu2_d4r"/><path class="sturihscz"/><path class="mk93lqrnh"/><path class="hzm2gxbyj"/><path class="ywoqp9dou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:task-merge-duotone-thin" {...props}></Icon>
<style>
:global(.ar5lnnlvf) {
  fill: currentColor;
  d: path("M13 5.5A2.5 2.5 0 0 1 15.5 3h3A2.5 2.5 0 0 1 21 5.5 2.5 2.5 0 0 1 18.5 8h-3A2.5 2.5 0 0 1 13 5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.e03qxmiyg) {
  fill: currentColor;
  d: path("M3 5.5A2.5 2.5 0 0 1 5.5 3h3A2.5 2.5 0 0 1 11 5.5 2.5 2.5 0 0 1 8.5 8h-3A2.5 2.5 0 0 1 3 5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.h95es8zjt) {
  fill: currentColor;
  d: path("M3 16.5A2.5 2.5 0 0 1 5.5 14h13a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-13A2.5 2.5 0 0 1 3 16.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hzm2gxbyj) {
  d: path("M17 8v6");
}

:global(.mk93lqrnh) {
  d: path("M7 8v6");
}

:global(.n9mu2_d4r) {
  d: path("M3 5.5A2.5 2.5 0 0 1 5.5 3h3A2.5 2.5 0 0 1 11 5.5 2.5 2.5 0 0 1 8.5 8h-3A2.5 2.5 0 0 1 3 5.5");
}

:global(.sturihscz) {
  d: path("M13 5.5A2.5 2.5 0 0 1 15.5 3h3A2.5 2.5 0 0 1 21 5.5 2.5 2.5 0 0 1 18.5 8h-3A2.5 2.5 0 0 1 13 5.5");
}

:global(.ywoqp9dou) {
  d: path("M3 16.5A2.5 2.5 0 0 1 5.5 14h13a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-13A2.5 2.5 0 0 1 3 16.5");
}

</style>

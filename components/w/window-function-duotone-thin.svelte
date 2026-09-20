<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ks3ax8u7u"/><path class="d1ogaqb9m"/><path class="pnk8nclld"/><path class="wcg-7deem"/><path class="oviel8bwg"/><path class="ou9p_ybmc"/><path class="k9n1nabge"/><path class="m45ql5bta"/><path class="s1n7yd_mp"/><path class="s92gxib6y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:window-function-duotone-thin" {...props}></Icon>
<style>
:global(.d1ogaqb9m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 10h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k9n1nabge) {
  d: path("M3 10h12.5");
}

:global(.ks3ax8u7u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m45ql5bta) {
  d: path("M3 16h12.5");
}

:global(.ou9p_ybmc) {
  d: path("M3 4h12.5");
}

:global(.oviel8bwg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18.5 7H21v12h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pnk8nclld) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s1n7yd_mp) {
  d: path("M3 22h12.5");
}

:global(.s92gxib6y) {
  d: path("M18.5 7H21v12h-2.5");
}

:global(.wcg-7deem) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 22h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

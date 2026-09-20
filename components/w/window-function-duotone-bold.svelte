<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ocp3vlnry"/><path class="f1zulcwmv"/><path class="pxvf-t9uc"/><path class="giptpm6xw"/><path class="s51vi28sr"/><path class="ou9p_ybmc"/><path class="k9n1nabge"/><path class="m45ql5bta"/><path class="s1n7yd_mp"/><path class="s92gxib6y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:window-function-duotone-bold" {...props}></Icon>
<style>
:global(.f1zulcwmv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 10h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.giptpm6xw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 22h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k9n1nabge) {
  d: path("M3 10h12.5");
}

:global(.m45ql5bta) {
  d: path("M3 16h12.5");
}

:global(.ocp3vlnry) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 4h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ou9p_ybmc) {
  d: path("M3 4h12.5");
}

:global(.pxvf-t9uc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s1n7yd_mp) {
  d: path("M3 22h12.5");
}

:global(.s51vi28sr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18.5 7H21v12h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s92gxib6y) {
  d: path("M18.5 7H21v12h-2.5");
}

</style>

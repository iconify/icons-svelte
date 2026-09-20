<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j-atgz8yl"/><path class="sej2a9tve"/><path class="qhpk1fjmd"/><path class="x2dazdbms"/><path class="fdvd1zxtb"/><path class="ou9p_ybmc"/><path class="k9n1nabge"/><path class="m45ql5bta"/><path class="s1n7yd_mp"/><path class="s92gxib6y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:window-function-duotone-regular" {...props}></Icon>
<style>
:global(.fdvd1zxtb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18.5 7H21v12h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j-atgz8yl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k9n1nabge) {
  d: path("M3 10h12.5");
}

:global(.m45ql5bta) {
  d: path("M3 16h12.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ou9p_ybmc) {
  d: path("M3 4h12.5");
}

:global(.qhpk1fjmd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s1n7yd_mp) {
  d: path("M3 22h12.5");
}

:global(.s92gxib6y) {
  d: path("M18.5 7H21v12h-2.5");
}

:global(.sej2a9tve) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 10h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x2dazdbms) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 22h12.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

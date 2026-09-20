<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ou9p_ybmc"/><path class="k9n1nabge"/><path class="m45ql5bta"/><path class="s1n7yd_mp"/><path class="s92gxib6y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:window-function-outline-regular" {...props}></Icon>
<style>
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

:global(.s1n7yd_mp) {
  d: path("M3 22h12.5");
}

:global(.s92gxib6y) {
  d: path("M18.5 7H21v12h-2.5");
}

</style>

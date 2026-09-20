<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t7dts892l"/><path class="eh8a4lk-c"/><path class="rynhfyfxm"/><path class="rrwm8uaph"/><path class="j2d9j4b0r"/><path class="miurf-h0g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:weed-duotone-thin" {...props}></Icon>
<style>
:global(.eh8a4lk-c) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12 8 8h4L8 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j2d9j4b0r) {
  d: path("M12 12 8 8h4L8 4");
}

:global(.miurf-h0g) {
  d: path("M5 18h14");
}

:global(.rrwm8uaph) {
  d: path("M12 4v14");
}

:global(.rynhfyfxm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 18h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t7dts892l) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
